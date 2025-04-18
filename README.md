# Cross-Repo Dependency Analyzer

A tool to analyze dependency graphs across multiple repositories within an organization.

## Overview

This tool automates the process of discovering and visualizing dependencies between repositories in an organization. It helps teams understand cross-repository dependencies to better manage changes and updates across a codebase ecosystem.

## Features

- Automatically scans repositories within an organization
- Analyzes package.json files to identify dependencies
- Generates visual dependency graphs
- Commits visualization results back to the repository

## Usage

To trigger a dependency analysis:
1. Create a new issue with the title "update dependencies"
2. The GitHub workflow will automatically run and generate a new dependency graph
3. Results will be committed back to the repository as an SVG file in the `/visualizations` directory

## Example

This tool can be used to analyze dependencies across React-related repositories in the facebook organization to understand how they depend on each other.