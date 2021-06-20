# springboot-jwt-api-security
How to secure your SprinbBoot Rest API using JWT authentication Code Example

# Download springboot-jwt-api-security.zip file, extract it and build with maven or import in IDE as a maven project

#YouTUbe Video Link (understand in Details) : https://youtu.be/c_c_guJlhsk
Genertae JWT Toke URL : http://localhost:8080/authenticate


Request PayLoad for Generate Token (Method Name-> Post) : 
{
	"userName":"techtalk",
	"passWord":"password"
	
}

Hit the Actual /hello API to Consume the API response by Token(Method Name -> Get) :

API URL : http://localhost:8080/hello

Put "Authorization" in headers then value should be Bearer "generated token"
