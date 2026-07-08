# n8n Workflow Documentation Lab

## Overview

This lab explores the structure and configuration of several n8n workflows by documenting each node, its purpose, settings, inputs, outputs, and how it contributes to the workflow.

The objective was to become familiar with different workflow patterns and understand how data flows between nodes in n8n.

## Workflows Analysed

### 1. Simple AI Agent
A conversational AI workflow consisting of:

- Chat Trigger
- AI Agent
- OpenAI Chat Model
- Simple Memory
- MCP Client

The workflow accepts user messages, processes them using an AI Agent connected to an OpenAI model, stores conversation context with Simple Memory, and can optionally access external tools through an MCP Client.

---

### 2. AI to Notion Workflow

This workflow demonstrates how AI-generated content can be automatically saved into Notion.

Nodes include:

- AI Agent
- OpenAI Message Model
- Create Notion Page

The generated response is used as both the page title and page content.

---

### 3. Scheduled Email Workflow

This workflow uses a Schedule Trigger to automatically execute on a defined schedule.

It demonstrates how workflows can be automated without requiring manual user interaction.

---

## Deliverables

This repository contains:

- Workflow documentation spreadsheet
- Node screenshots
- README
- Lab summary

## Skills Demonstrated

- Understanding n8n workflow structure
- Reading node configurations
- Identifying inputs and outputs
- AI Agent workflows
- OpenAI integrations
- Notion integration
- Memory nodes
- MCP Client configuration
- Scheduled workflow automation

## Author

David Gill

Ironhack AI Engineering Bootcamp
