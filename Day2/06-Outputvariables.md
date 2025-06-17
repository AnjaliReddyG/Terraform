output "example_output" {
  description = "An example output variable"
  value       = resource.example_resource.example.id
}

//
Output variables allow you to expose values from your module or configuration, making them available for use in other parts of your Terraform setup.

output is used to declare an output variable named example_output.
description provides a description of the output variable.
value specifies the value that you want to expose as an output variable. This value can be a resource attribute, a computed value, or any other expression.
//
