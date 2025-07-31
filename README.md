# AWS Landing Zone Accelerator Configuration

This repository contains configuration files for AWS Landing Zone Accelerator (LZA), providing a comprehensive set of AWS security, compliance, and governance controls.

## Configuration Files

- `accounts-config.yaml` - Account structure and organizational units
- `global-config.yaml` - Global settings and logging configuration
- `iam-config.yaml` - IAM roles, policies, and permission sets
- `network-config.yaml` - VPC, subnets, and networking configuration
- `organization-config.yaml` - AWS Organizations and service control policies
- `security-config.yaml` - Security services and compliance controls

## Usage

1. Review and customize each configuration file according to your requirements
2. Deploy using AWS Landing Zone Accelerator pipeline
3. Monitor deployment through AWS CodePipeline

## Prerequisites

- AWS Organizations enabled
- AWS Control Tower (optional but recommended)
- Appropriate IAM permissions for deployment

## Security

These configuration files contain infrastructure-as-code definitions. Review all settings before deployment and ensure they align with your security requirements.