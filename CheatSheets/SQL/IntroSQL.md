# Introduction to SQL

    SQL = Structured Query Language

## Basics of SQL

- Key words of the language are usually written in `capital`

- Identifiers such as table names or column are usually written in `lowercase` or `mixte case`

### Basic operations

- `SELECT`
    - example : 
        ```sql 
                SELECT name 
                FROM users;
        ```
- `INSERT`
    - example : 
        ```sql 
                INSERT INTO users (name, mail) 
                VALUES ('Jean', 'jean@example.com');
        ```

- `UPDATE`
    - example : 
        ```sql 
                UPDATE users 
                SET mail = 'nouveau@example.com'
                WHERE name = 'Jean';
        ```

- `DELETE`
    - example : 
        ```sql 
                DELETE FROM users 
                WHERE name = 'Jean';
        ```

### Data types

- **INT** : whole numbers
- **VARCHAR** : string with undefined size
- **CHAR** : fixed size string
- **TEXT** : high length string
- **DATE** : for dates
- **TIME** : for hours
- **TIMESTAMP** : to save a precise moment
- **FLOAT**,**DOUBLE** : decimal numbers
- **DECIMAL** : for monetary values or when precision is mendatory
- **BLOB** : stock binary data such as images or media files
- **BOOLEAN** : True or False data