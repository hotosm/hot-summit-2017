# HOT Summit 2016 - Adding new events

For each event the ```type``` field will determine how the event shows up on the schedule.

| Field        | Changees       | 
| ------------- | -------------:|
| type      | "admin", "session", or "split-session" |


## Admin

Administrative events, such as Registration or Breaks that don't require a description or definition.


| Field        | Changees       | 
| ------------- | -------------:|
| time      | When the event occurs      |
| event | Title of the event  |
| location | Where the event is taking place   |

## Session

For all talks that take place that are open to everyone at the summit. Speaker names will link to the speakers page.

| Field        | Changees       | 
| ------------- | -------------:|
| speakers:      |   |
| -name      | Name of the speakers      |
| -org | Organization affiliated with that speaker  |
| description | Description of the events   |

When there are multiple speakers (like with lightning talks), you can write them in like so:

```
speakers:
- name: Example Speaker 1
  org: HOT
- name: Example Speaker 2
  org: NFL
- name: Example Speaker 3
  org: NBA

...etc
```

## Split-Session

For the break out sessions. There are the same fields here as are in session, but there are 'a' & 'b' versions.
