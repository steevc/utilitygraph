# utilitygraph
Plotting my energy consumption. This is using the API from Octopus Energy https://developer.octopus.energy/docs/api/

Write config file with something like:

import json

data = {'api_key':'xxx',
    'emeter_mpan':'xxx',
    'emeter_serial':'xxx',
    'gmeter_mprn':'xxx',
    'gmeter_serial':'xxx',
       }

with open("meters.json", "w") as outfile:
    json.dump(data, outfile)
