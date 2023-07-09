# Email Verifier

This is a simple email verification tool written in Go. It checks various DNS records associated with an email domain to determine if the domain has valid MX, SPF, and DMARC records. The tool provides information about the presence of these records for a given email domain.

## Prerequisites

Before using this tool, make sure you have the following prerequisites installed:

- Go programming language (at least version 1.16)
- Internet connection to perform DNS lookups

## Usage

To use the email verifier tool, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/your-repository.git
   ```

2. Change into the project directory:

   ```shell
   cd your-repository
   ```

3. Run the tool:

   ```shell
   go run main.go
   ```

4. Enter an email domain and press Enter. The tool will perform DNS lookups to check the presence of MX, SPF, and DMARC records for the domain.

   The tool will display the verification results in a tabular format. The table columns represent the following information:

   - **Domain**: The email domain being checked.
   - **MX**: Indicates whether the domain has valid MX records (`true` or `false`).
   - **SPF**: Indicates whether the domain has a valid SPF record (`true` or `false`).
   - **SPF Record**: The SPF record associated with the domain, if available.
   - **DMARC**: Indicates whether the domain has a valid DMARC record (`true` or `false`).
   - **DMARC Record**: The DMARC record associated with the domain, if available.

5. Repeat step 4 to verify additional email domains.

6. To exit the tool, press `Ctrl+C`.

## Troubleshooting

If you encounter any errors while using the tool, ensure that you have a stable internet connection and that the email domains you are verifying are valid. If the issues persist, please check the error messages displayed by the tool and consult the Go documentation for troubleshooting assistance.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Acknowledgments

Special thanks to the Go community for providing excellent tools and libraries that made the development of this email verifier possible.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on the [GitHub repository](https://github.com/AadiXC0DE/EmailVerification).
