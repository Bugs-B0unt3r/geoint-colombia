# GEOINT Tools for Colombia

This document contains a list of tools and platforms that allow for GEOINT analysis focused on Colombia.

## 1. National Civil Registry (Registraduría Nacional del Estado Civil)
- **Description**: Allows you to check voter registration locations using a Colombian ID.
- **URL**: [Registraduría](https://wsp.registraduria.gov.co/censo/)
- **Use case**: Geolocation of voters and polling places.

## 2. SIPLAFT - Integrated System for Prevention of Money Laundering and Financing of Terrorism
- **Description**: Tool for identifying businesses and individuals to prevent money laundering.
- **URL**: [SIPLAFT](https://www.siplaft.com/)
- **Use case**: Identifying individuals and companies linked to potential illicit activities within specific areas.

## 3. Superintendency of Notary and Registration (Superintendencia de Notariado y Registro)
- **Description**: Provides access to property and real estate records in Colombia.
- **URL**: [SNR](https://www.supernotariado.gov.co/)
- **Use case**: Geospatial analysis of real estate and land registration.

## 4. IGAC - Agustín Codazzi Geographic Institute
- **Description**: Provides maps and geospatial information on the Colombian territory.
- **URL**: [IGAC](https://www.igac.gov.co/)
- **Use case**: Advanced geospatial analysis of urban and rural areas.

## 5. Multipurpose Cadastre
- **Description**: Offers updated cadastral information for properties across Colombia.
- **URL**: [Multipurpose Cadastre](https://www.catastromultiproposito.gov.co/)
- **Use case**: Access to property and land registry data.

## 6. IDEAM - Institute of Hydrology, Meteorology, and Environmental Studies
- **Description**: Provides meteorological and environmental data, including interactive maps on Colombia.
- **URL**: [IDEAM](http://www.ideam.gov.co/)
- **Use case**: Environmental and climate analysis.

## 7. TransMilenio System
- **Description**: Location of stations and routes for Bogotá’s TransMilenio system.
- **URL**: [TransMilenio](https://www.transmilenio.gov.co/)
- **Use case**: Analysis of urban mobility and public transportation in Bogotá.

## 8. SIAC - Environmental Information System of Colombia
- **Description**: Provides geospatial and environmental information for Colombia.
- **URL**: [SIAC](http://www.siac.gov.co/)
- **Use case**: Natural resources management and sustainability analysis.

## 9. Geoportal Colombia
- **Description**: The official platform for geospatial data in Colombia.
- **URL**: [Geoportal](https://geoportal.igac.gov.co/)
- **Use case**: Thematic maps and detailed geospatial data.

## 10. Bogotá Stratification Consultation
- **Description**: A service to check the socioeconomic stratification of different areas in Bogotá.
- **URL**: [Bogotá Stratification](https://www.shd.gov.co/shd/estratificacion)
- **Use case**: Socioeconomic analysis of urban areas.

# how use:

This flowchart outlines the process of selecting and using the various GEOINT tools in your repository. You can include this markdown in the relevant part of your documentation to help users navigate the available tools efficiently.

# GEOINT Tools Usage Workflow

```mermaid
graph TD
    A[Step 1: Explore Tools Documentation] --> B[Choose a Tool]
    B --> C[Option 1: Registraduría Nacional]
    B --> D[Option 2: SIPLAFT]
    B --> E[Option 3: Superintendencia de Notariado]
    B --> F[Option 4: IGAC]
    B --> G[Option 5: Multipurpose Cadastre]
    B --> H[Option 6: IDEAM]
    B --> I[Option 7: TransMilenio System]
    B --> J[Option 8: SIAC]
    B --> K[Option 9: Geoportal Colombia]
    B --> L[Option 10: Bogotá Stratification]
    C --> M[Apply Tool for GEOINT Analysis]
    D --> M
    E --> M
    F --> M
    G --> M
    H --> M
    I --> M
    J --> M
    K --> M
    L --> M
    M --> N[Contribute Findings Back to the Repository]
