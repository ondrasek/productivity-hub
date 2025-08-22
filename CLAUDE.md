# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

This is a productivity management system designed to leverage Claude Code, MCP servers, and other AI tools to support:
- Daily/weekly planning, reviews, and task management
- Learning management (backlog, newsletters, YouTube content, flashcards, research)
- Personal wellness (reflection journaling, gratitude, habit formation)

## Project Management

- Use GitHub issues for task tracking and work management
- This repository is hosted on GitHub at github.com/ondrasek/productivity-hub

## Development Approach

### MCP Server Development
When developing MCP servers for this project:
1. Follow the MCP (Model Context Protocol) specification
2. Create servers that can integrate with existing productivity tools and services
3. Prioritize Claude Code compatibility

### Architecture Principles
- Leverage existing open-source tools and cloud services where possible
- Develop custom solutions only when necessary
- Design for extensibility through MCP servers, APIs, and tool integrations

### Sub-agents and Slash Commands
When implementing Claude Code customizations:
- Design sub-agents for specific productivity domains (planning, learning, wellness)
- Create slash commands for frequently used operations
- Ensure clear documentation for each custom component

## Key Integration Points

- Claude Code as the primary AI interface
- MCP servers for external system integration
- GitHub for version control and issue tracking
- Potential integration with OpenCode, Aider, and other AI tools as secondary options