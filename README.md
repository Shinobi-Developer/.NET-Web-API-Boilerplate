<p align="center">
  <img src="https://github.com/Shinobi-Developer/.NET-Web-API-Boilerplate/assets/133488886/711125f3-335c-423c-9eac-0bdff15b85e3" alt="No background"/>
</p>

# .NET Web API Boilerplate

This is a boilerplate project for creating a .NET Web API using C#.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine
2. Open the solution file in Visual Studio
3. Build the solution to restore the NuGet packages
4. Run the project

## Features

- A basic .NET Web API structure
- Swagger documentation to test the API endpoints
- JWT authentication for secure API calls
- Logging using Serilog

## Dependencies

The project has the following dependencies:

- .NET Core 3.1
- Swashbuckle.AspNetCore (for Swagger)
- Microsoft.AspNetCore.Authentication.JwtBearer (for JWT authentication)
- Serilog.AspNetCore (for logging)

## Configuration

The project has the following configuration options:

- `JwtSettings:SecretKey` - the secret key used to sign and verify JWT tokens
- `JwtSettings:Issuer` - the issuer of the JWT tokens
- `JwtSettings:Audience` - the audience of the JWT tokens
- `Logging:LogFilePath` - the path of the log file

These options can be set in the `appsettings.json` file or via environment variables.

## Contributing

Contributions are welcome! If you find a bug or want to add a feature, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
