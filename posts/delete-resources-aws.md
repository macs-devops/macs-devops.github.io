# Delete AWS resources

At my job we are deleting aws accounts and resources, mostly deployed with Terraform.  
Eventually, when wanting to delete an object, we run into dependencies, with versioned buckets with some objects and various complications that we find along the way.  
:confused:  
The first thing one thinks is that a <pre><code>terraform destroy</code></pre> is enough, but it is not.
  
  
Other alternatives were also tools like aws-nuke and cloud-nuke.
The executions of these tools were not entirely successful.  
  
  


