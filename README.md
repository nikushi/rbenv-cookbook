rbenv-cookbook
=======================

Chef cookbook for rbenv and ruby-build

Requirements
------------

#### depends
- `yum-epel`

Attributes
----------

#### rbenv-cookbook::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['rbenv-cookbook']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### rbenv-cookbook::default
TODO: Write usage instructions for each cookbook.

e.g.
Just include `rbenv-cookbook` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[rbenv-cookbook]"
  ]
}
```

Contributing
------------
TODO: (optional) If this is a public cookbook, detail the process for contributing. If this is a private cookbook, remove this section.

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: TODO: List authors
