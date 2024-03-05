# Helm cheat sheet

A list of useful commands, params etc. for the Helm CLI

**Creation** 

| Command | Description |
|---------|-------------|
| helm create &lt;name&gt; | Create a initial helm project |


**Install/Uninstall Charts**

| Command | Description |
|---------|-------------|
| helm install &lt;name&gt; &ltchart&gt; | Install a chart with the given name |
| helm uninstall &lt;name&gt;  | Uninstall a chart using the given name |
| helm install &lt;name&gt; &ltchart&gt; --dry-run | Dry run an install a chart with the given name |

**General** 

| Command | Description |
|---------|-------------|
| helm list | Lists the release |
| helm show &lt;command&gt; | Show's information about the chart |

