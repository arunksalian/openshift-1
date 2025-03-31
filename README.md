Simple openshift dev

oc login --token=sha256~78tnXq8ZSOxqxWCrJE1mAiRk1svIfgsWTDJ7v4TTFck --server=https://api.rm2.thpm.p1.openshiftapps.com:6443
curl -H "Authorization: Bearer sha256~78tnXq8ZSOxqxWCrJE1mAiRk1svIfgsWTDJ7v4TTFck" "https://api.rm2.thpm.p1.openshiftapps.com:6443/apis/user.openshift.io/v1/users/~"
