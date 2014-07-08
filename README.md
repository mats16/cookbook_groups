groups Cookbook
====================
This cookbook makes groups.

Requirements
------------

- nothing

Data Bags
----------
This cookbook create users from "groups" data_bag information.

#### groups::hogehoge.json
```json
{
  "id": "hogehoge",
  "groupname": "hogehoge",
  "gid": "100"
}
```

Usage
-----
#### groups::default
Just include `groups` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[groups]"
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
