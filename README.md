# Nuclei Templates

This repository contains a collection of Nuclei templates that can be used to perform automated security testing.

## About Nuclei

[Nuclei](https://nuclei.projectdiscovery.io/) is a fast and customizable vulnerability scanner that allows you to quickly identify vulnerabilities in web applications, APIs, and infrastructure. It uses templates to define the behavior of the scanner and can be easily integrated into your security testing workflow.

## Using the Templates

To use these templates with Nuclei, you will need to have Nuclei installed on your system. You can then clone this repository and use the `-t` flag to specify the location of the templates when running Nuclei.

For example:

```
nuclei -t /path/to/nuclei-templates/ -target https://example.com
```

## Contributing

Contributions to this repository are welcome! If you have created a Nuclei template that you would like to share with the community, please feel free to open a pull request.