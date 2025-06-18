variable "example_var" {
  description = "An example input variable"
  type        = string
  default     = "default_value"
}

// 
Input variables are used to parameterize your Terraform configurations. They allow you to pass values into your modules or configurations from the outside.
Input variables can be defined within a module or at the root level of your configuration.

variable is used to declare an input variable named example_var.
description provides a human-readable description of the variable.
type specifies the data type of the variable (e.g., string, number, list, map, etc.).
default provides a default value for the variable, which is optional.
//

eg)
# variables.tf
variable "instance_type" {
  type    = string
  default = "t2.micro"
}
