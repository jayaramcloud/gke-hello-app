# gke-hello-app

Login to GKE:
```
jay@SHAW073312:~/.kube$ gcloud config set account jayadmin@kubetrain.com
Updated property [core/account].
```

To take a quick anonymous survey, run:
  $ gcloud survey

```
jay@SHAW073312:~/.kube$  gcloud auth login
Go to the following link in your browser:

    https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=32555940559.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=openid+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fuserinfo.email+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcloud-platform+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fappengine.admin+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcompute+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Faccounts.reauth&state=UXzsSp0LUxAq2WSboI&prompt=consent&access_type=offline&code_challenge=e1T57GmijdxMfM-wWPdkZC9__OFJOMxsA&code_challenge_method=S256

Enter verification code: 4/1AX4XfWjr65vhkEvTC65n35n35ynm35nm35eQs5nhIjcZ9VGBPNeeQ

You are now logged in as [jayadmin@kubetrain.com].
Your current project is [None].  You can change this setting by running:
  $ gcloud config set project PROJECT_ID
```
```
jay@SHAW073312:~/.kube$ gcloud projects list
PROJECT_ID              NAME              PROJECT_NUMBER
galvanized-pipe-333904  My First Project  870893455952
gleaming-block-333902   My First Project  201847224768
kubetrain-331123        kubetrain         387873934739
```

```
jay@SHAW073312:~/.kube$ gcloud config set project kubetrain-331123
Updated property [core/project].

jay@SHAW073312:~/.kube$ kubectl get nodes
NAME                                             STATUS   ROLES    AGE     VERSION
gke-virtusa-cluster-default-pool-808e0d91-hpdj   Ready    <none>   16d     v1.21.5-gke.1302
gke-virtusa-cluster-default-pool-808e0d91-lpcl   Ready    <none>   4d23h   v1.21.5-gke.1302
```

