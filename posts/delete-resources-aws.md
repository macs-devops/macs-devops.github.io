# Delete AWS resources

At my job we are deleting aws accounts and resources, mostly deployed with Terraform.  
Eventually, when wanting to delete an object, we run into dependencies, with versioned buckets with some objects and various complications that we find along the way.  
:confused:  
The first thing one thinks is that a <code>terraform destroy</code> is enough, but it is not.
  
  
Other alternatives were also tools like <code>aws-nuke</code> or <code>cloud-nuke</code>.
The executions of these tools were not entirely successful.  
  
  
I found some tools that I think are interesting and with which I started some tests.  
  
[awsls](https://github.com/jckuester/awsls)  
  
  
[awsrm](https://github.com/jckuester/awsrm)  
  
  
[awsweeper](https://github.com/jckuester/awsweeper)
  
  
I don't really know if it's some aws control mechanism or what, but I haven't been able to do a massive deletion of my account's resources.  
  
  
:sweat_smile: In these days I will conclude the tests and update this post.

