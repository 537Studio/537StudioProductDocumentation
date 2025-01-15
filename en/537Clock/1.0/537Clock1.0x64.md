# 537 Clock 1.0

> For 64-bit portable version

## Table of Contents
- [Introduction](#Introduction)
- [Download](#Download)
- [Installation](#Installation)
- [Help](#Help)
- [Development](#Development)

## Introduction

537 Clock is a Windows console application developed by 537 Studio, featuring a command-line interface with displays for date and time, Unix timestamp, timing/reset, and color adjustment functionalities.

It is designed for convenient timing, time checking, and viewing Unix timestamps.

The 64-bit version 1.0 was released on December 31, 2023.

## Download

> Size: 1.84MB

- [537 Studio Official Website](https://www.537studio.com)
- [Gitee](https://gitee.com/FTS-537Studio/537Clock/releases/tag/v1.0)
- [GitHub](https://github.com/537Studio/537Clock/releases/tag/v1.0)


## Installation

This software is a portable program. Once downloaded, it can be used immediately and can be moved around as a regular file.

## Help

### Frequently Asked Questions

#### Software Not Trusted

##### In Browser

- Please expand the “More” option (if available) in the warning window and choose “Keep Anyway” or “Trust.”

##### In System

- If a system pop-up displays “Unverified Publisher,” click on “More Info” in the window and then select “Run Anyway.”
- If an antivirus software reports a threat, choose “Trust” or “Allow to Run,” or exit the antivirus software and try again.

#### Unable to Run

##### Displays “Unverified Publisher” or Reported by Antivirus

- Please refer to the “Software Not Trusted” section.

##### Only an Empty Black Window Pops Up and No Response for a Long Time After Launch

- Please close the window and restart the software.
> Ensure that only one instance of the software is running. If multiple windows appear, close them one by one, leaving only one.
- If the computer shows no response after launching the software, wait for a moment, or exit the antivirus software and try again.

#### Display Abnormality After Narrowing the Window

- This is a software bug that has been fixed in version 1.1 and later updates.

#### Chinese Display Garbled

##### Occurs in Operating Systems Other Than Windows

- When using Wine, try modifying the Wine console settings to display using ANSI encoding (or GBK and GB2312).
- Adjust the encoding for other software as well.

##### Occurs in Windows Environment

- Ensure that the system has correctly installed the Simplified Chinese language pack.

### Contact Us
- hello@537studio.com
- wushaoquan666@outlook.com

## Development
- Gitee: https://gitee.com/FTS-537Studio/537Clock
- GitHub: https://github.com/Sean537/537Clock

### Programming Language Used

- C++98

### Development Environment

- Editor: Dev-C++ 5.11
- Compiler: MinGW 4.9.2

> Since the software uses Win32API, it can only be built in a Windows operating system environment. Alternatively, it can be cross-compiled in environments like Linux.