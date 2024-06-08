# MIC - Memory analysis of IndexedDB data on Chromium-based applications

## Usage

```bash
usage: main.py [-h] [-d] [-q] [--log_file _LOG_FILE] memory_dump_file
```

## Description

This project is a codebase designed to parse and interpret structures related to IndexedDB from memory dumps of Chromium-based services. It utilizes the `deserializer` module from the `ccl_solution_group` library for value deserialization, specifically for `blink_value` and `v8_value`.

## Positional Arguments

- `memory_dump_file`: Path to the memory dump file in the Windows Minidump file format.

## Options

- `-h`, `--help`: Show this help message and exit.
- `-d`, `--debug`: Enable debug output.
- `-q`, `--quiet`: Disable informational output.
- `--log_file _LOG_FILE`: Path to the log file.

## Example Usage

```bash
python main.py memory.dmp 
```

## This project was submitted to `DFRWS APAC 2024` and will be made publicly available in the future.