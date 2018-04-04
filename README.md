# TinyFS

## Purpose

We want to build a tiny user-mode file system based on persistent memory in order to extract useful information from

PM-based file system.

## Aims

- It provides common interfaces for file operations (maybe not POSIX-like)
- It correctly works with file data persistent in PM
- It supports data consistence and data concurrency
- It supports individual configuration for users

## Data Organization

|  Super Metadata | File Metadata |  Data Region | Log Region |
| :-: | :-: | :-: | :-: |
| File System Metadata | Metadata for Files | File Data organized in Self-defined Chunks | Transaction Logs in Self-defined Chunks |

## Example Procedure

### What happens during the filesystem initiation?

### What happens during a directory creation?

### What happens during a file creation?

### What happens during a file read?

### What happens during a file write(append/modification)?

### To be added...

