---
title: "Calculator"
description: "A Windows desktop calculator built with C# and WinForms on .NET 8, with exact decimal arithmetic, full keyboard support and a tested core engine."
pubDate: 2026-10-20
tags: ["C#", ".NET 8", "WinForms", "MSTest"]
repoUrl: "https://github.com/catalindragusanu/Calculator1"
featured: true
---

## Overview

A small Windows desktop calculator that keeps its arithmetic separate from the UI, so the logic can be tested without opening a window.

## Key Features

- **Exact decimal arithmetic** - `0.1 + 0.2` is `0.3`, and integers up to 16 digits keep every digit
- **Pending operation display** - shows the operation in progress above the result, for example `8 ÷`
- **Clear error messages** - division by zero and out-of-range results are reported, not swallowed
- **Keyboard and accessibility** - full keyboard support and screen-reader names on every button

## Project Layout

- **Calculator.Core** - UI-independent arithmetic and the key-driven state machine
- **Calculator** - the WinForms shell: keypad layout and keyboard mapping
- **Calculator.Core.Test** - MSTest suite for the engine and the form wiring

## Tech Stack

- **Language**: C#
- **Framework**: .NET 8, WinForms
- **Testing**: MSTest
