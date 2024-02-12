--Installation

npm install -g artillery@latest
npm install artillery-plugin-expect

--Debugging

DEBUG=https:request artillery run corelation.yml
set DEBUG=http:response

--Assertions

set DEBUG=plugin:expect
artillery run my-script.yaml

--Reporting (Generate a JSON and convert to HTML)
 
 artillery run correlation1.yml --output smoke.json
 artillery report smoke.json

 C:\Users\kunal.malik\AppData\Roaming\npm\artillery run basic_pricing.yml