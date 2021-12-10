# Add your public SSH keys in the table (to be used for the remote connection from Laptop/Tablet to the Linux VM @server_bob)

1. Generate s ssk key pair (public & private key) on your local machine by typing via command line
```ssh-keygen -t rsa -b 4096``` (...the keys should look like something like this: rsa-ssh .....== user@userPC)
2. Add the content of your fresh generated public part of the ssh key-pair as pull-request to the table below


<br/>

**Choose & Commit ... 2 students per group**

|  Student Name	        |  Description		          	|  public ssh key  user 1  |  key user 2    |
| :-------------------: | :-------------------------: | :----------------------: | :------------: |
|Gin Havana             |ITA|                          |ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQCxK73DMPIGbPIJcwxufvJOgJ8ax6DMGXkIcUOCX0djYB7X6lPaNRJAATWs6c0uU97N8hZ26K3n0odd5tcroMhH/PUb0N0yv+S4oGUzCxfmTmUAH5aO55/AsBksGIe2NROCIU59Oef6rHA+iP+QYT23mgEaqDuW3I3lLh+s1sM40FLzshVTSrNpzR9O3QCxEPrFW1beYL9/xxK569GX94brBjsFaU19IBDXWYGDSD0Kngci4iqgonj8qdTpk8kM8H16ggyGPN+VtyZyS0Xz9iXJg82ddwCMJScRQj/b7hPwt+QHQax+Ke7K5Y+6h/kOPj6PL58xsHJ1FQD6JpHd/wC/g/fP70Y0a4lANWE2TpVi0bxOlVrfQBvQG9Q7qXEQHqf0lnNZAhx2glQWr4laVod3MNSNwZcMDp5wHZ75T885Fucq7sqWQAnbAmgNHIWuu7dT0jJAtmVSUYUO4oIWal1uYk5a4IPSCGxTR07YaW+D9mRn8wzqnWVogc541Bzp8s8jlgu0ExqAtSumImSQDT+CQ/YoG4W1EJkPuRM4tZK/bjjaTv94qTRV11b/4Ra1h4/J0NKV4onTZBfXhfUoxlID/4ccE0hopvYD+rM0Y0cypFbZ6gNfjbTbDENK+thN4zkwLmJn4lomQGwAJST3xjXoKV2+LWg3RKfO8crlX5TO8Q== ginhavana@Gin-Havana|
|                       |                             |                          |                |
| Dietrich Kaufmann     | INF FS3                     | ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDRuw6gvumDBy4RJCXPRayTOMohMdUKB/picq/E+4XcYDNNwlyOtBVV2AjqF3X+FEuxdE1TyCSdbAZAWCAn8C5s4PUrPdU2JISJj5EdYXS/jeSTVYhPMzquFgpyrJsOS/Y0X6N12ZHT9jr/6l4xTb9CcIiBMLx0aAZr1oq4AzVTqf4SHGxG9QcYHJWQxvSwKKr0HuxRCuJAFfnJmepB+2ico1pkIqYUngQkXGpkISmpfDKsF+RRAPGtbjLKn5zjxe+FkB7k6CUkjlta4Nz/aF6Po1cTRLBevfSKidya19l7AcHvinMMlHN6q8x2TjJEo6rVRrGtRJ6Zc8CtDJfhe0NaY4+b7+6CfRLVuxb7Hp8qa5WHkDDfqHyJjZPHa6Uy46jNr63koPweUjezcLVOE70jB4sd2DtB6+HChBlI9NSIoiH3dMt8jvKk4Vi0OXl7lrq2Qe/B91QXpbtI9vBEItO3mdB5GP6BZOO2+8Iz8IjReshJTPgA1Fi8Sli6EfQ1FPE= dk@LAB-PC01
|Arwed Paul Meinert     | ET                          | ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDvCfOp1U0q9iEO0UPqIwydfjUF/Wh5fG9FuMwErFvuTsTmpHOxCusbpH5ZvKMcPKTFXGll5uugBcz3AGzKT83GObzFD0ZGle8JlUPiUi2iTvlv9n9j5F++ZqU0emUpnCjm/6sfmnHphwJFl6SkelGs+MNAdKRwILVzRs0pFN11rFr2pya8yYDEmmadNRei800Scxbju2XAr7sS1EvKAcnmJFPQ6LPWQu54+HH1uaLAsBvT48n4fyHgxdCpZGWRIgO20+MqqLd8EliuPqPTtHb48gmBNb9z/dPyfQMlTsTx0yRyWViOTi5Jrbz5cAqunxByEfbmrvoLdUUK7ZEQbDLGyTnxTwK7t7qt0CJRlDqUP/LcULSOaE2+59d5KVmokYNtOpOd4TfY/9MpTPjAm2uVCZraY2zew/KR+QJXtk2tQHMuOz5HjxtzazJiLazqVXraeLl/3/FYmw16f20ow1R0zCCk/MfOfG1aGucXk+zsJq7dWrdL1+XRSAADK9sF/BLlHjJ2sP83CCCWVluSMuBhJr+CMQTJ2Cn3myr9ptERNmxN1CQ5eJYoNkzfQPr6MHf5HyRwi6SKGMOZ3OZTFgFHV4VLr7AppVPJnHAKLFQzeCpC/rdz1Qt/HMdmIQo/H+1eoz8yWuYWEWa6O5YqBF6cDoYonKtC9x7LWj7pgRa3wQ== arwedpaulmeinert@fedora
|                       |                             |                          |                |
|                       |                             |                          |                |
|                       |                             |                          |                |
|Niklas Hensel          |INF                          |ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCeETCcF03yZ8Ev1nPOCU3dqHQed4w5NZRJLIT1b0CtjzpoKrWjcbYw5e8U1K/n8YMypZLnqA2KDeXMOTOEfaeumRTywmlYOo9D9Rp4edK7X46hIVzWLSg46xZRpr5XvhRJ7fDRhOzeqvaV4VXXmDilmgS3nHaaG4dXhPzuooM3ALkr8yvJHqRDeX5MfROY9fgaaS563/9hZH5hMHFwRkUvf8CJzy5mEMPNTYjQrk+gyHNjx84sGk5SMEz6tJg+YzvLRYqDB+2WtR2Q1x8bZMm+yzTvD7ojKOWEJj+2Ln9bHuQ/QkK2N5b8MxsWLw8QRRhwCYtKUDWp6XhR5YV8HvsFMjTfb0wU9Zn07aYRKLlhCkC0dPhCkU1BQLEqTHwx8YsdDPEXsDMMpkBLI2TnW7YiHFikwJqIqXH1S4i1SpJFtIvwgbDa7pfqsEr37MZ9T29QXXInctUBEu/s6iD7SXTqQr8zc0eYRrmpARTfzKzivnUTzpyZQTmSvrsUt4M0Yk8= nikla@PC-Niklas                          |                
