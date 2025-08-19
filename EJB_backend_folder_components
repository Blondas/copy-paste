# EJB Backend Folder Components

## Overview
The backend folder contains database-specific configuration and mapping files for EJB-to-DB2 mapping on AIX platform systems.

## File Components

### DB2AIX.dbm
**Database Model File**
- Logical representation of DB2 database on AIX
- Contains DB2 AIX specific properties and connection parameters
- Stores database metadata and Unix environment characteristics

### ibm_pmbab.properties
**Configuration Properties**
- Database connection settings (JDBC URLs, drivers, authentication)
- IBM mapping tool configurations
- AIX-specific parameters (character encodings, file paths, library locations)

### Map.mapxmi
**Object-Relational Mapping**
- XMI format mapping definitions
- Maps EJB entity attributes to database columns
- Defines relationships, inheritance, and constraints
- Used by IBM tools for code generation

### Table.ddl
**Database Schema Definition**
- DDL script with CREATE TABLE statements
- Includes primary/foreign keys, indexes, constraints
- Uses standard DB2 syntax optimized for AIX/Unix environments

## Purpose
Acts as the **bridge** between Java EJB entities and physical DB2 database, providing:
- Database connectivity configuration
- Schema definition and generation
- Object-relational mapping metadata
- DB2 AIX platform optimizations
