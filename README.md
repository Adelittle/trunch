# Trunch - URL path truncation

## Overview

The URL Path Truncation Tool is a powerful utility that allows you to manipulate and explore URLs by gradually removing parts of the URL path. This tool helps you simplify and navigate complex URLs to reach higher-level or contextually relevant URLs that you desire.

## Features

- Gradually remove segments of the URL path to achieve shorter and more general URLs
- Gain a higher-level perspective of the URL structure
- Easily explore different URL variations and paths
- Integration with Fuzzing and Crawling tools for enhanced capabilities

## Installation

```
git clone https://github.com/Adelittle/trunch/
cd trunch
chmod +x trunch
```

## Usage

Single Target
```
echo http://example.tld/mobil/harga/bbm/ | ./trunch

Result
http://example.tld/mobil/harga/bbm/
http://example.tld/mobil/harga
http://example.tld/mobil
```

List Target
```
cat list.txt | ./trunch
```
