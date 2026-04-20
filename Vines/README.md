# Factory Digitization for MES Integration, Barcode Automation, and Label Printing

A **factory digitization project** for the VinES factory under Vingroup, focused on streamlining production data flow by **processing MES data**, **extracting APIs**, and **automating barcode generation** and **label printing** for inner-box tracking. The system was designed to reduce manual entry, improve traceability, and standardize labeling workflows across manufacturing operations.

## Overview

This project supports digital transformation in a factory environment by connecting production data from the MES layer to downstream operational tasks such as barcode generation, box identification, and printing standardized labels. Instead of relying on manual transcription and disconnected software steps, the workflow centralizes production information and automatically converts it into printable tracking labels.

The implemented solution targets inner-box labeling use cases, where each label contains structured fields such as Model, Capacity, Batch No, Rank, Quantity, Date, Remark, and a Tracking area for barcode or traceability content. This enables more reliable packaging control and easier integration between shop-floor execution and inventory tracking.

## Objectives

- Process and normalize MES data for packaging and traceability workflows.
- Extract and connect APIs for production-related data exchange.
- Automate barcode generation from MES-driven fields.
- Generate print-ready labels for inner-box packaging.
- Reduce human error in manual labeling and data re-entry.
- Improve traceability across production, packing, and logistics.

## Key Features

- MES data parsing and structured field mapping.
- API extraction and integration for real-time data exchange.
- Automatic barcode generation for tracking identifiers.
- Label template automation based on factory packaging format.
- Standardized inner-box label output for printing workflows.
- Support for production metadata such as batch number, quantity, and date.

## Workflow

### MES Data Processing

The system collects production-related information from MES sources and converts raw records into structured data fields required by packaging operations. This step ensures that key attributes such as product model, batch number, quantity, production date, and classification data are normalized before label generation.

### API Extraction and Integration

Production data is exposed or consumed through APIs so that labeling logic can operate automatically instead of depending on manual spreadsheet entry. This makes it possible to connect MES records with downstream printing tools, barcode services, or operator-facing applications in a more scalable way.

### Barcode and Label Automation

After the MES fields are processed, the system generates barcode content for the tracking section and inserts all required values into the label template. The automated template follows the inner-box format, including fields for Model, Capacity, Batch No, Rank, Q’ty, Date, Remark, and Tracking.

### Printing Operation

The final label is formatted for direct printing, helping operators generate consistent box labels without manually editing each record. This improves speed on the packaging line and reduces formatting inconsistencies between shifts or workstations.

## Label Structure

The label template is based on an inner-box layout with the following production fields:

- Model
- Capacity
- Batch No
- Rank
- Q’ty
- Date
- Remark
- Tracking

These fields support both human-readable inspection and machine-readable traceability through barcode content.

## Impact

- Reduced manual workload in packaging and labeling operations.
- Improved data consistency between MES and printed labels.
- Faster label preparation for inner-box packaging.
- Better traceability for production batches and box-level tracking.
- Easier standardization of factory digitization workflows.

## Tech Scope

- MES data processing
- API integration
- Barcode generation
- Label template automation
- Print workflow standardization
- Factory traceability digitization
