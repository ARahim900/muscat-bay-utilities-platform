# Muscat Bay Utilities Platform

A comprehensive utilities management platform for Muscat Bay including:

## Modules

### Water System (Current)
- Interactive dashboard for monitoring water consumption and loss
- Zone-specific analysis for identifying problem areas
- Usage type analysis for understanding consumption patterns
- Loss analysis for identifying leakage points
- System hierarchy visualization

### Future Modules (Planned)
- Electricity monitoring
- STP Plant management
- Contractor tracking
- HVAC/BMS integration
- Asset Lifecycle Management (ALM)

## Water System Dashboard

The water system dashboard provides comprehensive monitoring of water consumption and loss analysis for Muscat Bay. It includes:

- **Dashboard Overview**: Key metrics for total supply, consumption, and loss
- **Zone Analysis**: Detailed monitoring of different geographical areas
- **Type Analysis**: Understanding consumption patterns by usage type
- **Loss Analysis**: Identifying potential leakage points
- **System Hierarchy**: Visual representation of water flow through the system

## Getting Started

### Running the Water System Dashboard

1. Navigate to the water-system directory
```
cd water-system
```

2. Install dependencies
```
npm install
```

3. Start the development server
```
npm start
```

4. Place your data file in the appropriate location

## Data Format

The water system dashboard expects CSV data in the following format:

- Meter Label: String
- Acct #: String
- Zone: String
- Type: String
- Parent Meter: String
- Label: String (L1, L2, L3, DC)
- Monthly consumption data columns (Jan-24, Feb-24, Mar-24, etc.)
