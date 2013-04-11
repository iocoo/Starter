README
Step 1.
  install git
 you can use the following commands(Ubuntu linux):

  $ apt-get install git
Step 2.
  setting ssh key and push into Github.com

  $ssh-keygen  -t rsa -C 'yourmail@mail.com'

 and then you may get this information:

	Generating public/private rsa key pair.
	Enter file in which to save the key (/home/xxx/.ssh/id_rsa): key
	Enter passphrase (empty for no passphrase): 
	Enter same passphrase again: 
	Your identification has been saved in key.
	Your public key has been saved in key.pub.
	The key fingerprint is:

 
  $ ssh-add 'your-key'

Step 3.

  test connction 
  
  $ git git@github.com

  if Success you may see:
  ERROR: Hi xxx! You've successfully authenticated, but GitHub does not provide shell access
Connection to github.com closed.


OK>....



