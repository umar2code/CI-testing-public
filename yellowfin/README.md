# Test Cases for yellowfin

```
	Background:
		Given I can parse "/arm_dist/azuredeploy.json" json
	Scenario: Key contains a value.
		When $schema is the key on template file
		Then Its value should contain 2015-01-01/deploymentTemplate.json

		When parameters.password.value is the key on params file
		Then Its value should contain yellowfin@123
    
    ```

	
Commits:
1
2
3a
ss
3
ss
2
s
3
d
dd
s
2
