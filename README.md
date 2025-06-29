# 🚀 JMeter-Project - OrangeHRM Performance Testing Suite

Welcome to the **JMeter-Project** – a robust and modular performance testing framework designed for **OrangeHRM** using Apache JMeter. This project helps simulate real-world user scenarios and generate insightful reports using CSV datasets, assertions, and dynamic scripting.

---

## 📌 Key Features

- ✅ **Modular Test Plan**: Organized by PIM, Time, and Admin modules with separate thread groups.
- 📂 **CSV Data-Driven Testing**: Read user and product data from CSV files to simulate realistic scenarios.
- 💡 **Assertions & Validations**: Includes JSON, XPath, and response code assertions for validation.
- 📈 **Integrated Reporting**: Summary reports in HTML and custom Python analytics with bottleneck detection.
- 🔧 **Custom JSR223/Groovy Scripts**: Smart pacing, conditional flows, and dynamic parameterization.
- 🐳 **Docker Support**: Run tests with InfluxDB + Grafana stack for live monitoring and visualization.

---

## 🧪 Modules Covered

| Module | Description |
|--------|-------------|
| 🔸 **PIM**      | Add, search, and delete employee records using dynamic data |
| 🔸 **Time**     | Timesheet submission and approval simulation |
| 🔸 **Admin**    | Manage users and roles, search records, and audit activities |

---

## 🛠️ How to Use

### 🧰 Prerequisites

- [Apache JMeter 5.6.3](https://jmeter.apache.org/)
- Java 8+ installed and configured
- Git installed (`git clone`)
- Python (for analytics scripts)
- Docker (optional for InfluxDB + Grafana)

### 🚀 Launch Tests via Command Line

```bash
jmeter -n -t test.jmx -l results/result.jtl -e -o reports/
