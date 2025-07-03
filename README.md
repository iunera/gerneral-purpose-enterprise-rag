# General Purpose Enterprise RAG

This repository contains architectural documentation and diagrams for building a generic Natural Language Web (NLWeb) RAG (Retrieval-Augmented Generation) system with extension points for enterprise use.

## Overview

The project demonstrates how to design and implement a flexible, extensible RAG system that can be adapted for various enterprise scenarios. The architecture includes extension points that allow customization for different use cases while maintaining a solid core foundation.

## Production Implementation

This NLWeb RAG architecture has been successfully implemented in production at [iunera.com](https://www.iunera.com) and is actively [used with data from the  Corporate blog](https://www.iunera.com/kraken/), demonstrating its real-world effectiveness and scalability.

## Files in this Repository

### Architecture Diagrams

#### Source Diagram
- **[howto-build-a-generic-nlweb-rag-with-extension-points-generic.drawio](./howto-build-a-generic-nlweb-rag-with-extension-points-generic.drawio)** - The main Draw.io source file containing all architectural diagrams

#### Exported Diagrams

##### Ingestion Flow
![Ingestion Flow](./howto-build-a-generic-nlweb-rag-with-extension-points-generic-Ingestion%20flow.drawio.png)

This diagram illustrates the data ingestion pipeline for the RAG system, showing how documents and data sources are processed, indexed, and made available for retrieval.

##### NLWeb Normal Flow
![NLWeb Normal Flow](./howto-build-a-generic-nlweb-rag-with-extension-points-generic-NLWeb%20Normal%20Flow.drawio.png)

This diagram shows the normal operational flow of the Natural Language Web interface, demonstrating how user queries are processed, relevant information is retrieved, and responses are generated.

## Architecture Components

The system is designed with the following key principles:
- **Modularity**: Clear separation of concerns with well-defined interfaces
- **Extensibility**: Extension points allow customization without modifying core components
- **Scalability**: Architecture supports horizontal scaling for enterprise workloads
- **Flexibility**: Adaptable to different data sources, retrieval methods, and generation models

## Usage

1. Open the Draw.io file to view and edit the complete architectural diagrams
2. Reference the exported PNG files for quick visualization of specific flows
3. Use these diagrams as a blueprint for implementing your own enterprise RAG solution

## Contributing

When making changes to the architecture:
1. Update the main Draw.io file
2. Export updated PNG files for any modified diagrams
3. Update this README if new components or flows are added
