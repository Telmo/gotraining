## Concurrency Patterns
There are lots of different patterns we can create with goroutines and channels. Two interesting patterns are resource pooling and concurrent searching.

## Notes

* The work code provides a pattern for giving work to a set number of goroutines without losing the gaurentee.
* The resource pooling code provides a pattern for managing resources that goroutines may need to acquire and release.
* The search code provides a pattern for using multiple goroutines to perform concurrent work.

## Links

http://blog.golang.org/pipelines

https://talks.golang.org/2012/concurrency.slide#1

https://blog.golang.org/context

http://blog.golang.org/advanced-go-concurrency-patterns

## Code Review

[Work](work)

[Pooling](pool)

## Advanced Code Review

[Search](search)

___
[![GoingGo Training](../00-slides/images/ggt_logo.png)](http://www.goinggotraining.net)
[![Ardan Studios](../00-slides/images/ardan_logo.png)](http://www.ardanstudios.com)
[![GoingGo Blog](../00-slides/images/ggb_logo.png)](http://www.goinggo.net)
___
All material is licensed under the [GNU Free Documentation License](https://github.com/ArdanStudios/gotraining/blob/master/LICENSE).