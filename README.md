# gridtastic-lite
A super basic responsive CSS starterkit

Custom OOKB CSS framework. Provides basic responsiveness, a simple grid, and some basic type and reset styles

The practical deology behind how this works takes a lot of inspiration from things like Bootstrap and Skeleton... but tries to simplify things a bit.

Your outer most tag for width limited responsive section should use the "container" class. "Container" will provide a fixed-width main width. "Container-fluid" can also be used to create something that always spans the full available width of the browser/parent.

When you are planning on using columns inside a container, create a child to the container with the class of "group" (we also respect the "row" class from things like bootstrap, but we find "group" to be more semantically useful).

Columns are attempted to be written with semantic classes to make it clear what they are doing. The default is a twelve column grid. Things can be easily changed to be less or more (more exlanations to come). For example, to create a column that spans 6 of the twelve columns, write ```<div class="six columns">```

```
<div class="container">
  <div class="group">
    <div class="six columns">
    </div>
  </div>
</div>
```

More instructions, rules, guideliens — whatever — to come.
