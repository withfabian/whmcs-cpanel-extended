
---

# ModulesGarden cPanel Extended For WHMCS

ModulesGarden's **cPanel Extended For WHMCS** is a comprehensive WHMCS module that allows for seamless integration of essential cPanel functionalities directly within WHMCS, enabling efficient management of web hosting accounts and services.

## Features

### Admin Area
- **Account Management**: Create, suspend, unsuspend, and terminate accounts.
- **Package Control**: Change package and account password.
- **Direct Access**: Log in to cPanel accounts and WHM with one click.
- **Security**: Automatically unban client IP addresses upon login.
- **Initial Settings**: Configure initial settings and resource limits for accounts and email.
- **Product Customization**: Configure features and templates per product.
- **Resource Limits**: Limit resource usage with CloudLinux integration, including PHP version, virtual memory, and operations per second.
- **Application Auto Installer**: Enable and configure Softaculous or Installatron auto-installer per product.

### Client Area
- **Remote Access & Management**:
  - Domains: Addon domains, domain aliases, redirects, subdomains.
  - Applications: Installation, backup, staging, and cloning (Softaculous and Installatron).
  - Emails: Accounts, forwarders, autoresponders, deliverability, mailing lists.
  - Files: File Manager, FTP accounts, disk usage, Git version control.
  - Databases: MySQL and PostgreSQL management, Remote MySQL.
  - Security: SSL/TLS management, IP blocker, SSH access, ModSecurity.
  - Metrics: Latest visitors, Webalizer, AWStats, Analog stats.
- **One-Click Logins**: Access cPanel, File Manager, phpMyAdmin, RVSiteBuilder, Webmail, WP Toolkit.
- **WordPress Management**: Requires WordPress Manager For WHMCS, allowing control over WordPress instances and plugins.
- **Bulk Actions**: Manage multiple components simultaneously.
  
### Application Auto Installer
- **Ordering Process**: Auto-install applications after account creation.
- **Client Area**: Softaculous or Installatron app installation, app backups, staging, and cloning.
- **Backup & Restore**: Create and manage backups of installed applications.

### Integrations
- **CloudLinux**: Configure per-product limits.
- **DNS Manager**: Supports cPanel DNS and DNSOnly.
- **IP Manager**: Control and assign IP subnets.
- **Server Allocator**: Auto-assign suitable servers to products.
- **Billing Integration**: Advanced billing based on server resource usage.
- **Themes**: Supports Lagom WHMCS Client Theme and WHMCS themes "Six" and "Twenty-One".

## System Requirements
- **WHMCS**: Version 8.6 - 8.9
- **PHP**: Version 7.4 - 8.1
- **ionCube Loader**: Version 12 or later

## Installation
1. **Download**: Obtain the module package from [ModulesGarden](https://www.modulesgarden.com/).
2. **Upload**: Extract the package and upload it to the `/modules/addons` directory in your WHMCS installation.
3. **Activate**: In the WHMCS Admin area, navigate to **Setup** > **Addon Modules** and activate **cPanel Extended For WHMCS**.
4. **Configure**: Access the module settings to configure product features, limits, and integrations.

## Usage
Once installed, admins can create, manage, and configure cPanel accounts directly from WHMCS, and clients can access an extended suite of cPanel tools in the client area.

## Documentation
For full documentation, visit the [ModulesGarden Documentation](https://www.docs.modulesgarden.com/).



