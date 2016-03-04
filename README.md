# Submit your school's course data here!

For more information of this project, visit the project [page](http://lorix-lpan.github.io/perfect-schedule) and
[repo](https://github.com/lorix-lpan/perfect-schedule)

### Specifications
Make sure to read it before make a pull request!
```
// teachers.json
[
  {
    // note: it is also okay if you format name as "John Doe", just make sure to be consistent
    "val": "Doe, John"
  },
  {
    "val": "Pan, Lawrence"
  }
  // ...
]
```
```
// codes.json
[
  {
    "val": "SSS-LAQ"
  },
  {
    "val": "SSS-LBQ"
  }
  // ...
]
```
```
// courses.json
[
  {
    // It does not have to be like that for your school, just make sure to be consistent!
    "val": "CALCULUS I"
  },
  {
    "val": "GENERAL BILOGY I"
  }
  // ...
]
```
```
// details.json
[
  {
    "section": "00001",
    "meeting": [
      {
        // Make sure the time and day attributes are exactly the same as the following!
        // Be consistent!
        "day": "M",
        "time": ["14:15", "16:15"],
        "room": "G-202"
      },
      {
        "day": "TH",
        "time": ["14:15", "15:45"],
        "room": "A-315"
      }
    ],
    "name": "GENERAL BIOLOGY II",
    "teacher": "Di Flumeri, Celestino",
    "code": "101-LCU-05"
  }
]
```

Note: Duplication is not allowed!
