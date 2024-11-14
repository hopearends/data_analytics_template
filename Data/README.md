# Data

## Folders

---

#### Source data: link here

#### Raw

Original, unmodified data after dowloading, scraping, etc.

#### Processing

Data that is in the process of being cleaned and analyzed.

#### Final

Data after all cleaning, processing and analyzing is done.

---

#### Data Dictionary

| Field Name   | Data Type | Description                                             | Example                 | Constraints                  |
| ------------ | --------- | ------------------------------------------------------- | ----------------------- | ---------------------------- |
| `id`         | Integer   | A unique identifier for each entry in the dataset.      | `12345`                 | Primary Key, Not Null        |
| `name`       | String    | The name of the entity or object being described.       | `"John Doe"`            | Not Null                     |
| `age`        | Integer   | The age of the entity or object.                        | `29`                    | Must be a positive integer   |
| `email`      | String    | The email address associated with the entity or object. | `"johndoe@example.com"` | Must be a valid email format |
| `created_at` | DateTime  | The timestamp of when the entity or object was created. | `2024-01-01 10:00:00`   | Not Null                     |
| `is_active`  | Boolean   | Flag indicating whether the entity is currently active. | `True`                  | Default: `True`              |
| `address`    | String    | The address of the entity or object (if applicable).    | `"123 Main St, City"`   | Optional                     |
| `latitude`   | Float     | Latitude coordinate for the address (if applicable).    | `40.7128`               | Optional, Range: [-90, 90]   |
| `longitude`  | Float     | Longitude coordinate for the address (if applicable).   | `-74.0060`              | Optional, Range: [-180, 180] |
