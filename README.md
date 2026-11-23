# domain-intelligence-scanner
Open-source domain intelligence tool for researching expired domains, historical websites, company-name matches and online brand presence.
# Domain Intelligence Scanner

An open-source research application for evaluating expired and potentially available domain names.

## Project purpose

Domain Intelligence Scanner helps researchers identify domain names that warrant further investigation based on naming quality, online presence, historical usage and company-name matches.

## Features

- Import large CSV and TXT domain lists.
- Perform automated preliminary domain screening.
- Shortlist promising candidates for deeper investigation.
- Search for exact-name mentions and related online evidence.
- Identify historical website records where available.
- Export structured research results.

## Architecture

The application uses a Python FastAPI backend, a background processing worker and a browser-based interface.

## Research integrations

- Tavily Search API — web research.
- Internet Archive — historical website research.
- OpenCorporates — planned company-record research integration.

## Research principles

Search-engine mentions are not automatically verified businesses. Company-name matches are not proof of trademark ownership or domain availability.

The project is intended to support evidence-based research, including potential commercial domain-investment decisions.

## Project status

Working local prototype. Open-source documentation and further integrations are in development.

## Licensing

The application source code is intended for release under the MIT License, subject to a final code and dependency review. Third-party data remains subject to the applicable provider licences.
