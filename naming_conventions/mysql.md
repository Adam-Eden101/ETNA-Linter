# MySQL Naming Conventions

## General Rules

- Use lowercase.
- Use underscores instead of spaces.
- No numbers or special characters.
- Names should be in english names.
- Names should be self-explanatory and as short as possible.
- Avoid prefix.
- Be consistent.

## Database

- Name should be singular.

## Tables

- Names can be singular or plural, but be consistent. It's either one or the other.

## Field Names

- Names shouldn't be longer than two words.
- Names should be easy and understandable.
- Primary key can be id or table name_id or it can be a self-explanatory name.
- Avoid using reserve words as field name. i.e. — Pre-defined words or Keywords. You can add prefix to these names to make it understandable like user_name, signup_date.
- Avoid giving both the table and a field the same name.
- Avoid abbreviated, concatenated, or acronym-based names.
- Do define a foreign key on database schema.
- Foreign key column must have a table name with their primary key. (e.g. blog_id represents foreign key id from table blog).
- Avoid semantically — meaningful primary key names. A classic design mistake is creating a table with primary key that has actual meaning like ‘name’ as primary key. In this case if someone changes their name then the relationship with the other tables will be affected and the name can be repetitive losing its uniqueness.
