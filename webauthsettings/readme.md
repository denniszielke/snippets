CLIENTIDPARAM="0a24f3d5-ded0-4749-8f7a-9a5187dc41b0"
ISSUERPARAM="https://someurl"

BODY=$(eval echo "'$(curl https://raw.githubusercontent.com/denniszielke/snippets/master/webauthsettings/armauth.json)'")
echo $BODY