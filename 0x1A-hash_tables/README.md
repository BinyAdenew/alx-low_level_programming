# C - Hash tables

In this project, I learned about hashing by implementing hash functions and hash tables in C.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files.

## Header File :file_folder:

* [hash_tables.h](./hash_tables.h): Header file containing definitions and prototypes for all types and functions written for the project.

Data Structures:
```
typedef struct hash_node_s
{
	char *key;
	char *value;
	struct hash_node_s *next;
} hash_node_t;

typedef struct hash_table_s
{
	unsigned long int size;
	hash_node_t **array;
} hash_table_t;

typedef struct shash_node_s
{
