# Organizations

## Branches

Contentstack provides **Branches** to allow you to create multiple copies of your stack content. Every stack has a *main branch* by ~~default~~. To create a new branch, you can fork a branch off of the main branch.
When you create a branch for the first time, the main branch becomes your _source branch_. For all subsequent branches you create, you need to specify a source branch from which it will __inherit data__.

* [Create a Branch](#create-a-branch)
* [Create an Alias](#create-an-alias)
* [Remove an Alias](#remove-an-alias)

> **Note**: The *Branches* feature is only available in the [new Contentstack interface](https://www.contentstack.com/docs/new-contentstack "Venus Interface").

Branches are useful for:
* Content managers
* Developers
* Admins
  * Org owners
  * Release managers
---
### Create a Branch
To create a branch, log in to your account, go to your stack, and perform the following steps:
1. Click the “Settings” icon on the left navigation panel, and select **Branches**.
2. Click on **+ New Branch**.
3. Enter a unique ID for the branch.
4. Select a branch from the dropdown from which this new branch should inherit data.
5. Click on **Create** to save your branch.
---
The following code block shows structure of the `single line textbox` element:
```json
{
    "data_type": "text",
    "display_name": "Single line textbox",
    "uid": "single_line",
    "field_metadata": {
        "description": "",
        "default_value": ""
    },
    "format": "",
    "error_messages": {
        "format": ""
    },
    "multiple": false,
    "mandatory": false,
    "unique": false
}
```
```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```
---
Image example:
![Markdown Logo](https://markdown-here.com/image/icon256.png)

---
Table sample:

| type    | default | optional |
| :------- | :------- | :-------- |
| boolean | true    | yes      |

---

Task list:
* [x] Task 1
* [x] Task 2
* [] Task 3

---

