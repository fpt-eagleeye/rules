# YARA_Rules

Collection of YARA signatures tested by FPT EagleEye Team

## What is YARA?
YARA is a tool that identifies malware by creating descriptions that look for certain characteristics. Each description can be either a text or a binary pattern. These descriptions are called “rules”. And by using rules that specify regex patterns, YARA enables the detection of specific patterns in files that might indicate that the file is malicious.

By using hex patterns, plain text patterns, wild-cards, case-insensitive strings, and special operators, YARA rules can be incredibly diverse and effective at detecting a wide range of malware signatures.

## Prerequisite
You can use one of these following tools to use Yara rules:
1. [YARA](https://yara.readthedocs.io/en/latest/gettingstarted.html#compiling-and-installing-yara)
2. [Loki - Scanner for Simple Indicators of Compromise](https://github.com/Neo23x0/Loki/releases)

For more information, go here https://github.com/InQuest/awesome-yara#tools

## Basic usage

For YARA, try this
```
Syntax:
yara [OPTIONS] RULES_FILE TARGET

Example:
yara top10malware/5_wannacry.yar -r /mnt/malware_repo

Parameters : 
  -r --recursive  Recursively search for directories
```

## Ruleset

- Top10malware
