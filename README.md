# UserRegistrationDemo

curl -X POST \
  http://localhost:8290/user-registration/register \
  -H 'cache-control: no-cache' \
  -H 'content-type: application/json' \
  -H 'postman-token: b38ec64d-f308-fcd6-0df3-3d23d0769327' \
  -d '{"name":"Bob",
	"email":"bob@wso2.com",
	"city":"Colombo",
	"phone": "+94123456",
	"id":"1",
	"userroles" :  [{"role" : "admin"}, {"role": "devop"}]
}'
