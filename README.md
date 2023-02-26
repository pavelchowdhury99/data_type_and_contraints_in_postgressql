# Data Types and Constraints In PostGresSQL

## Data Types

###  [Numerical data](https://www.postgresql.org/docs/current/datatype-numeric.html)
#### Without decimal values
1. SMALLINT
2. INTEGER
3. BIGINT

#### With exact decimal
1. NUMERIC(precision, scale)
   OR
   DECIMAL(precision, scale)


#### With inexact decimal
1. REAL - (6 digit precision)
2. DOUBLE PRECISION - (15 digit precision)

#### Serial Numbers
1. SMALLSERIAL
2. SERIAL
3. BIGSERIAL

### [Monetary](https://www.postgresql.org/docs/current/datatype-money.html)
1. MONEY

### [Character](https://www.postgresql.org/docs/current/datatype-character.html)
1. CHAR(n)/ CHARACTER(n)
2. VARCHAR(n)/ CHARACTER VARYING(n)
3. TEXT

### [TIME](https://www.postgresql.org/docs/current/datatype-datetime.html)
1. TIMESTAMP with and without time stamp
2. TIME with and without time stamp
3. DATE
4. INTERVAL

### [BOOLEAN](https://www.postgresql.org/docs/current/datatype-boolean.html)
1. BOOLEAN

### [ENUMERATE](https://www.postgresql.org/docs/current/datatype-enum.html)
1. ENUMERATE

### [JSON](https://www.postgresql.org/docs/current/datatype-json.html)
1. JSON

### [ARRAYS](https://www.postgresql.org/docs/current/arrays.html)

### [BUNDLE DATA TYPE](https://www.postgresql.org/docs/current/rowtypes.html)

### [GEOSPATIAL DATA](https://www.postgresql.org/docs/current/datatype-geometric.html)
