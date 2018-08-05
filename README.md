# create-public-repo-test

Perhaps because I canceled my monthly subscription it appears as though the
abiltiy to create new Public repos from the web interface has been suspend. When clicking 'new repository' 
I'm directed to a 500 page and when trying to access remote repos from my command I receive an error indicating:
"remote: your account is disabled. Please see https://github.com/account/billing."; however, that commit was
associated with a private repo so (which I can't access until I fix you account billing info and start my subsription again).

Meanwhile, while it seems the only way to create an empty remote repo is from the web interface and there is no git command for this;
I was able to succesfully create a remote empty repo from my command line using their API.
So in the meantime I will be issuing the folling command:

issuing the following command.

```
curl -u 'MyUserName' https://api.github.com/user/repos -d '{"name":"name-of-repo-i-want-to-create-"}'

Until I get things sussed with my acct. 

Test succussful!

