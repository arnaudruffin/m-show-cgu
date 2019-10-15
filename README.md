oc new-app https://github.com/arnaudruffin/m-show-cgu.git --name "something"
oc expose svc/something --hostname=something.com --labels 'network=public'
