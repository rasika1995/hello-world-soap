### README

#### POST REQUEST

<soapenv:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:urn="urn:examples:helloservice">
<soapenv:Header/>
<soapenv:Body>
<urn:sayHello soapenv:encodingStyle="http://schemas.xmlsoap.org/soap/encoding/">
<firstName xsi:type="xsd:string">Rasika</firstName>
</urn:sayHello>
</soapenv:Body>
</soapenv:Envelope>

end point - http://localhost:3000/helloworldservice
Body - raw/xml

#### GET REQUEST

end point - http://localhost:3000/helloworldservice?wsdl