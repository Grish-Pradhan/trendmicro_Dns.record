# DNS Records Analysis for trendmicro.com

This project provides an HTML-based report that analyzes the DNS records for `trendmicro.com`. It includes detailed tables that display various types of DNS records such as A Records, MX Records, NS Records, and notable TXT Records.

## Project Structure

- **HTML file**: The main file of the project is `trendmicro.html`, which contains the DNS records data for `trendmicro.com`.
- **CSS styling**: The report is styled using internal CSS for readability and aesthetics.

## DNS Records Overview

The following sections are included in the analysis:

1. **A Records**
   - Displays the IP addresses associated with `trendmicro.com`.

2. **MX Records**
   - Displays mail exchange records, including the mail servers for handling email traffic.
   - Shows priority and mail server names.

3. **NS Records**
   - Lists the nameservers responsible for the domain's DNS queries.
   - Includes Akamai nameservers used by `trendmicro.com`.

4. **TXT Records**
   - Displays notable TXT records used for domain verification and service authentication.
   - Includes services such as SPF, Google, Microsoft, Apple, and others.

## Output Example

Here’s a sample output of the DNS record analysis:

### A Records
| Record Type | Value            |
|-------------|------------------|
| A           | 150.70.232.194   |

### MX Records
| Priority | Mail Server                             |
|----------|-----------------------------------------|
| 10       | sjdc-itpf-01.udc.trendmicro.com         |
| 10       | sjdc-itpf-02.udc.trendmicro.com         |
| 10       | sjdc-itpf-03.udc.trendmicro.com         |
| 10       | sjdc-itpf-04.udc.trendmicro.com         |

### NS Records
| Nameserver             |
|------------------------|
| a5-67.akam.net          |
| a22-66.akam.net         |
| a3-66.akam.net          |
| a1-159.akam.net         |
| a18-64.akam.net         |
| a24-65.akam.net         |

### Notable TXT Records
| Service    | Purpose                                  |
|------------|------------------------------------------|
| SPF        | Email authentication policy             |
| Google     | Multiple site verifications             |
| Microsoft  | Domain verification                     |
| Atlassian  | Domain verification                     |
| DocuSign   | Domain verification                     |
| Adobe      | IDP site verification                   |
| Cisco      | CI domain verification                  |
| MongoDB    | Site verification                       |
| Apple      | Domain verification                     |
| Dynatrace  | Site verification                       |
| Salesforce | Organization ID                         |
| GlobalSign | Multiple domain verifications           |

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Grish-Pradhan/trendmicro_Dns.record/trendmicro.html
   ```

2. **Open the HTML File**:
   - Open `trendmicro.html` in any modern web browser to view the DNS record analysis.

3. **Modify or Extend**:
   - You can add new sections or modify the existing content if you want to analyze DNS records for other domains.
   - Feel free to update the CSS or HTML for customization.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Contributions are welcome! If you want to improve or extend the project, feel free to fork the repository and submit a pull request. Make sure to follow best practices and provide relevant information about the changes you make.



