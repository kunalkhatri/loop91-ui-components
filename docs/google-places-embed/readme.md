## How to use this component
1. Open UI Builder 
2. Click `Add Content` to open the component picker

    ![Component picker](ui-component-choser.png)
3. Configure your component

    ![Configure Component](component-configure.png)


### Technical details of configurations

#### Markers properties
```
schema : {
				"type":"array",
				"items": {
					"type":"object",
					"properties": {
						"id":{
							"type":"number"
						},
						"lattitude":{
							"type":"number"
						},
						"longitude":{
							"type":"number"
						},
						"label":{
							"type":"string"
						},
						"visible":{
							"type":"boolean"
						}
					}
				}

			  }
```

Initial Coordinates
```
schema : {
				"type":"object",
				"properties":{
					"lattitude":{
						"type":"number"
					},
					"longitude":{
						"type":"number"
					}
				}
			}
```
