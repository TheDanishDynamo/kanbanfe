# kanban front end
Project with sample kanban UI / Front Ends in various frontend languages and framework

## Why
Demonstrate implementation of front end in different languages and frameworks. The idea is that the code can be re-used in your own organization, so you don't have to pay for trello, asana and other external kanban boards.

## How
Sample front end implementation (wireframe) of a minimal kanban or scrum board, based on the sample datamodel

### Data Model
![kanban.png](kanban.png)

### Sample json (items)

```

[
    {
        "item_id": 1,
        "title": "Eat",
        "description": "Buy food and consume it",
        "status" : "To do",
        "ordinal": 1
    },
    {
        "item_id": 2,
        "title": "Sleep",
        "description": "Find bed and close eyes",
        "status" : "Done",
        "ordinal": 2
    },
    {
        "item_id": 3,
        "title": "Work",
        "description": "Go do something to get paid",
        "status" : "Doing",
        "ordinal": 3
    }
]

```

### Sample json (status)

```

[
    {
        "status": "To do",
        "ordinal": 1
    },
    {
        "status": "Doing",
        "ordinal": 2
    },
    {
        "status": "Done",
        "ordinal": 3
    }
]

```

## Wireframe 
Drawing for the UI for the sample data

![wireframe.jpg](wireframe.jpg)

