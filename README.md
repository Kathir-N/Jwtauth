-----------------------------------------------------------------------
post:-localhost:8080/authenticate
body
{
    "username":"admin",
    "password":"admin1234"
}
respose:
tokenvarum

get
localhost:8080/weather/health
chose->authtype->beartooken copy paste the response token from autheticate method it will return 200 with response

------------------------------------------------------------------


pom . xml
jjwt-api
jjwt-impl
jjwt-jackson
-----
secuirtyconfig
@enablewebsec
@enablemthodsec
class {
@autowired
JWTAuthFilet JWTFilet;
@Bean
filterchain(){
        http.addFilterBefore(jwtAuthFilter, UsernamePasswordAuthenticationFilter.class);

}

@Bean
Usereservice()
Paswordencoder()
authmanager()
authprovider
----
@componennt
AuthFilet extens onceperreqfilter
@Authowried
JWTUtil
@Override
doFilterInternal()
generatetoken{
getBeartoken
call jwtutil
autheticate
return dofilter.()/;
}

----

@Component
JwtUtl{

 generateotken(){
 subj,usetname,time,claism.campact()}

 valdatetoken({
 rveresse of the above}
///?? check


 istokenexptred()

 }












