# software
curl --location --request POST 'http://localhost:10001/ReqUserKyc/2.0/urn:txnid:INDR5t0RdKIs1gledFdkew71SbsnXmFt8yI' \

--header 'Authorization: Bearer 9cc9c242-6b81-456a-929c-1dea4ca07d1a' \

--header 'Content-Type: application/xml' \

--data-raw '<token:ReqUserKyc xmlns:token="http://npci.org/token/schema/">
<Head ver="2.0" ts="1652692591167" orgId="gmGLwtqNoh6xQPe4" msgId="4sX0GgRWdjdj9hmJn5qIIsmvaoEDRUIe"/>
<ReqDetails type="Type2">
<User>
<DeviceInfo>
<Tag name="MOBILE" value="919579761130" />
<Tag name="DEVICEID" value="8212941b20316a57" />
<Tag name="GEOCODE" value="" />
<Tag name="LOCATION" value="" />
<Tag name="IP" value="192.168.1.39" />
<Tag name="TYPE" value="Phone" />
<Tag name="ID" value="RP1A.200720.012" />
<Tag name="OS" value="ANDROID" />
<Tag name="APP" value="" />
<Tag name="CAPABILITY" value="" />
<Tag name="ISP" value="VI" />
<Tag name="OSVERSION" value="11" />
<Tag name="MANUFACTUFER" value="samsung" />
<Tag name="MODEL" value="SM-A225F" />
<Tag name="PACKAGENAME" value="org.tsp.token" />
<Tag name="MVERSION" value="11" />
</DeviceInfo>
<Details>
<Detail name="mobile" value="919579761130"/>
<Detail name="country" value="India"/>
<Detail name="kycType" value="MIN"/>
<Detail name="aadhaarConsent" value="Y"/>
<Detail name="userImage" value=""/>
</Details>
<Creds>
<Cred type="AADHAAR" subType="NUMBER">
<Datacode>VYTba4NQluGiDF0vbznCVtharm6+hpqAvahx00UYVeEiAO46oNEc6VoNYyO+kab9H80QonQFyN6Rjm7cgk4jqRhc3UKllX9rFQTrRZ1jMsPuJp1Fq9OsbLZK58UeAp89uD7obk7CnVtDnUsEnAUQX7egRshNcA1liBdUBrAjvOaJuEHzEsFgFmdI9Z2vAolE7QzK3LV5CeOlTmv8oKqNBJqBkEyFz1S7Z+jlYO3LD3RphhqMH7Cmy+ReYPvsy7IPRStWQzCUgfF6RHy+AYgTfrHOBx1XUVvq7aO2E0BbiWsd2xx7niW9VGUB3ow3mlKc+mRIrM4PbBUeG7VFdROlyOHsM8MJQ
</Datacode>
</Cred>
</Creds>
</User>
</ReqDetails>
</token:ReqUserKyc>'


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Open Android App with Data</title>
</head>
<body>
    <h2>Click below to open the app with data:</h2>
    <a href="intent://dao?leadId=id&docRef=Ref#Intent;scheme=das;package=com.sbi.das;end">
        Open App with Data
    </a>
</body>
</html>
