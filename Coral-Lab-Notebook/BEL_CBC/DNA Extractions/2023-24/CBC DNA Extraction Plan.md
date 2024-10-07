|        | Healthy | Diseased_Tissue | Diseased_Margin |
| ------ | ------- | --------------- | --------------- |
| 092023 | 64      | 19              | 26              |
| 112023 | 36      | 0               | 0               |
| 122023 | 36      | 0               | 0               |
| 012024 | 69      | 0               | 0               |
| 022024 | 32      | 2               | 2               |
| 042024 | 126     | 15              | 18              |
| 062024 | 31      | 4               | 2               |
| 082024 | 34      | 0               | 0               |
|        | 428     | 40              | 48              |

just focus on Brain corals or just on MCAV and PSTR

100 samples will all go on one run, so organize by species 


# Load necessary libraries
library(dplyr)
library(reshape2)

# Read the data from CSV file
data <- read.csv("organized_counts.csv")

# Standardize the Health_Status values
data <- data %>%
  mutate(Health_Status = case_when(
    tolower(Health_Status) == "healthy" ~ "Healthy",  # Combine into "Healthy"
    TRUE ~ Health_Status  # Keep other statuses unchanged
  ))

# Combine species into one name if needed
data <- data %>%
  mutate(Species = case_when(
    Species %in% c("Species A", "Species B", "Species C") ~ "Combined Species",
    TRUE ~ Species
  ))

# Create a contingency table
contingency_table <- table(data$Health_Status, data$Month_Year, data$Species)

# Convert to a data frame
counts_df <- as.data.frame(contingency_table)

# Rename the columns for clarity
colnames(counts_df) <- c("Health_Status", "Month_Year", "Species", "Count")

# Reshape the data to create a matrix
matrix_counts <- dcast(counts_df, Health_Status + Species ~ Month_Year, value.var = "Count", fill = 0)

# View the matrix
print(matrix_counts)

# Optional: Save the matrix to a CSV file
write.csv(matrix_counts, "counts_matrix_combined_health_status.csv", row.names = FALSE)












