# COMP2112-Lab1
## How console.table works

```
const courses = [
    { 'code': 'COMP2112', 'name': 'Advanced Client Side Scripting' },
    { 'code': 'COMP2084', 'name': 'Server Side Scripting' },
    { 'code': 'MGMT2008', 'name': 'Project Management for IT' }
];
console.table(courses);
```
Output would be:

(index) |code | name
------------ | ------------ | -------------
0 | COMP2112 | Advanced Client Side Scripting
1 | COMP2084 | Server Side Scripting
2 | MGMT2008 | Project Management for IT
