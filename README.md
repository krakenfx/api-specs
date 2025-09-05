# Kraken API Specifications

Official open-source specifications for the Kraken API ecosystem, including OpenAPI 3.0 standards for all Kraken services. For API documentation, visit: https://docs.kraken.com/.

## Overview

This repository contains comprehensive API specifications for Kraken's trading platform and related services. All specifications follow OpenAPI 3.0 standards and are organized by service domain.

## APIs

### Spot Trading REST API (`spot-rest/`)
Complete specification for Kraken's spot trading REST API, including:
- **Public endpoints**: Market data, asset information, order books, trades, OHLC data
- **Private endpoints**: Account management, trading operations, order management, funding
- **User data**: Account balances, trade history, ledger information
- **Trading**: Order placement, modification, cancellation, batch operations

### Futures REST API (`futures-rest/`)

Specification for Kraken's futures trading platform:
- **Authentication**: API authentication endpoints
- **Charts**: Chart data and market visualization
- **History**: Historical data and trade records  
- **Statistics**: Trading statistics and metrics
- **Trading**: Futures-specific trading operations

### OAuth API (`oauth/`)

OAuth 2.0 authentication and authorization specification:
- Authorization code flow
- Token management
- Scope definitions
- Client authentication

### OTC API (`otc/`)

Specification for institutional OTC trading:
- Quote request creation and management
- Active and historical quotes
- Client verification
- Exposure management
- Trading pair information

### Pay API (`pay/`)
Kraken Pay service specification:
- Payment request creation and management
- Payment transfers
- Paylink code generation and configuration
- Payment cancellation

**Main file**: `pay/openapi_v3.yaml`

## Viewing Specifications
You can view these specifications using any OpenAPI-compatible tool:
- [Swagger UI](https://swagger.io/tools/swagger-ui/)
- [Redoc](https://redoc.ly/)
- [Postman](https://www.postman.com/)
- [Insomnia](https://insomnia.rest/)

## Authentication
Most private endpoints require API key authentication. Refer to the [individual service specifications](https://docs.kraken.com/api/docs/guides/global-intro) on our website for detailed authentication requirements and permissions.

## Standards Compliance

- **OpenAPI Version**: 3.0.0 - 3.0.4
- **Format**: YAML
- **Validation**: All specifications should pass OpenAPI validation
- **Documentation**: Comprehensive descriptions for all endpoints, parameters, and schemas

## Support

For questions about these API specifications or the Kraken API:
- [Kraken API Documentation](https://docs.kraken.com/rest/)
- [Kraken Support](https://support.kraken.com/)

## License

These specifications are open-source and available for public use in accordance with Kraken's API terms of service.
