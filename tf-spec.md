## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | ~> 1.3.0 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | ~> 4.37.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 4.37.0 |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_ec2"></a> [ec2](#module\_ec2) | ../../modules/e2esa-module-aws-ec2 | n/a |

## Resources

| Name | Type |
|------|------|
| [aws_instances.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/instances) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_ami"></a> [ami](#input\_ami) | EC2 | `any` | n/a | yes |
| <a name="input_availability_zone"></a> [availability\_zone](#input\_availability\_zone) | n/a | `any` | n/a | yes |
| <a name="input_aws_region"></a> [aws\_region](#input\_aws\_region) | General | `any` | n/a | yes |
| <a name="input_createdby"></a> [createdby](#input\_createdby) | n/a | `any` | n/a | yes |
| <a name="input_ec2_names"></a> [ec2\_names](#input\_ec2\_names) | n/a | `any` | n/a | yes |
| <a name="input_lb_target_tags_map"></a> [lb\_target\_tags\_map](#input\_lb\_target\_tags\_map) | Tag map for the LB target resources | `map(string)` | `{}` | no |
| <a name="input_loop_cnt"></a> [loop\_cnt](#input\_loop\_cnt) | n/a | `any` | n/a | yes |
| <a name="input_project"></a> [project](#input\_project) | Tags | `any` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_aws_ebs_volume_id"></a> [aws\_ebs\_volume\_id](#output\_aws\_ebs\_volume\_id) | aws\_ebs\_volume volume\_id |
| <a name="output_aws_instance_arn"></a> [aws\_instance\_arn](#output\_aws\_instance\_arn) | aws\_instance arn |
| <a name="output_aws_instance_public_dns"></a> [aws\_instance\_public\_dns](#output\_aws\_instance\_public\_dns) | aws\_instance public\_dns |
| <a name="output_aws_instance_public_ip"></a> [aws\_instance\_public\_ip](#output\_aws\_instance\_public\_ip) | aws\_instance public\_ip |
| <a name="output_data_aws_instance_id"></a> [data\_aws\_instance\_id](#output\_data\_aws\_instance\_id) | data\_aws\_instance\_id |
| <a name="output_data_aws_instance_ids"></a> [data\_aws\_instance\_ids](#output\_data\_aws\_instance\_ids) | data\_aws\_instance\_ids |