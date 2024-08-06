# Nonprofit Newsletter Generator

Copyright © 2024 Tech Tavern LLC. All rights reserved.

## Project Overview

Welcome to the Nonprofit Newsletter Generator, a proprietary tool developed by Tech Tavern LLC. This innovative solution harnesses the power of CREWAI and EXA Search to create tailored newsletters for local nonprofits. Inspired by Alejandro AO's tutorial, we've adapted and enhanced the concept to meet the specific needs of our community organizations.

Our goal is to streamline the newsletter creation process for local nonprofits, allowing them to focus on their mission while still maintaining effective communication with their supporters. By leveraging advanced AI technologies, we're able to generate relevant, engaging content that resonates with each organization's unique voice and audience.

## Key Features

- Utilizes CREWAI for intelligent task management and collaboration
- Integrates EXA Search for comprehensive and up-to-date information gathering
- Customizable templates to match each nonprofit's branding and style
- Automated content curation based on the organization's focus areas
- User-friendly interface for easy input and customization

## Getting Started

To get up and running with the Nonprofit Newsletter Generator, you'll need Python 3.10 or newer (but not exceeding 3.13). We use Poetry for dependency management to keep things smooth and simple.

### Setting Up Your Environment

1. If you haven't already, install Poetry:
   ```
   pip install poetry
   ```

2. Clone this repository and navigate to the project directory.

3. Install the project dependencies:
   ```
   poetry lock
   poetry install
   ```

4. Create a `.env` file in the project root and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

### Customization

To tailor the generator to your specific needs:

- Adjust `src/newsletter_gen/config/agents.yaml` to fine-tune the AI agents' roles and capabilities
- Modify `src/newsletter_gen/config/tasks.yaml` to customize the newsletter creation workflow
- Update `src/newsletter_gen/crew.py` to incorporate any additional logic or tools
- Edit `src/newsletter_gen/main.py` to add custom inputs for your specific nonprofit clients

## Running the Generator

To start generating newsletters, run the following command from the project root:

```
poetry run newsletter_gen
```

This will initiate the CREWAI-powered process, coordinating the AI agents to research, write, and compile a newsletter tailored to your nonprofit's needs.

## How It Works

Our Nonprofit Newsletter Generator leverages a team of specialized AI agents, each with distinct roles in the creation process. These agents collaborate on tasks defined in `config/tasks.yaml`, from initial research to final editing. The `config/agents.yaml` file outlines each agent's unique capabilities and focus areas.

## Support and Feedback

If you encounter any issues or have suggestions for enhancing the Nonprofit Newsletter Generator, please don't hesitate to reach out to Tech Tavern LLC. We're committed to continually improving this tool to better serve our local nonprofit community.

## Legal Notice

This software is the property of Tech Tavern LLC. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited without the express permission of Tech Tavern LLC.

Let's work together to amplify the voices of our local nonprofits and strengthen our community bonds!