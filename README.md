autojobs-config-sample
======================

<h2>Overview</h2>

<p>Provides configurations (via a .yaml file) that the jenkins-autojob tool needs for the automatic creation of jobs.
</p>

<h2>Example usage in Jenkins as shell command</h2>

<pre>
jenkins-makejobs-git config.yaml
</pre>

#### For Secured Jenkins

When jenkins is secured then the `username` and `API token` of any admin can be used to authenticate autojobs

eg.
```shell
jenkins-makejobs-git -u admin1 -p 2951fa1a41693ca9b1d115637cb2c7a0 config.yaml
```

- `-u`  - specifies the jenkins user's username
- `-p` - specifies the API Token

see [jenkins-autojobs](https://pythonhosted.org/jenkins-autojobs/) for documentation on more command line parameters
