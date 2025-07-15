# PySpark Health Analytics Platform

## Status: TRANSFORMATIONS COMPLETED

Health analytics pipeline using PySpark, PostgreSQL, and Docker for CDC BRFSS data processing.

### Completed Features:
- CDC BRFSS transformation pipeline operational
- 1,000 records processed successfully
- Numeric codes converted to readable text
- Stable Docker infrastructure
- SQL view created for advanced analytics

### Data Transformation:
**Before:** `01,2,8,9,9`  
**After:** "Male aged 35-44 from Alabama who does not have diabetes and exercises"

### Results:
- 1,000 records from Alabama processed
- Age distribution: 35-44 years (37.6%), 45-54 years (23.0%)
- 5 variables transformed: State, Age, Gender, Diabetes, Exercise

## Usage:
```bash
git clone https://github.com/MarioRodrigoG/pyspark-health-analytics.git
cd pyspark-health-analytics
docker-compose up -d
# Jupyter: http://localhost:8888
