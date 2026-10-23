# dotuseful

A republished copy of the [dotuseful](https://sourceforge.net/projects/dotuseful/)
project from SourceForge, providing Swing `JTree` utilities for programmatically
populating and animating tree components.

The javadoc was lightly cleaned so the project could be deployed to Maven
repositories; no other changes were made beyond the original 2004 sources.

## Classes

Package `org.dotuseful.ui.tree`:

| Class | Purpose |
| --- | --- |
| `AutomatedTreeModel` | Tree model that can populate itself automatically. |
| `AutomatedTreeNode` | Node supporting automated/lazy population. |
| `SortedTreeNode` | Node that keeps its children sorted. |
| `MouseAdaptedTree` | `JTree` with enhanced mouse interaction handling. |
| `MouseAdaptedTreeMouseHandler` | The mouse listener backing `MouseAdaptedTree`. |

Package `org.dotuseful.util`:

| Class | Purpose |
| --- | --- |
| `ArrayMgr` | Array helper utilities. |

## Dependency

```xml
<dependency>
  <groupId>com.github.codemonstur</groupId>
  <artifactId>dotuseful</artifactId>
  <version>0.1</version>
</dependency>
```

## Building

```sh
make build
```

## License

Apache License 2.0 — original copyright belongs to the upstream author
**dkrukovsky**. This repository only republishes the work.
