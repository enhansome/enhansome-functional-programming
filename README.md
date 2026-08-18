# Awesome Functional Programming with stars

## Contents

* [Tutorials and Articles](#tutorials-and-articles)
  * [Lenses](#lenses)
  * [Monads](#monads)
  * [Purescript](#purescript)
  * [Elm](#elm)
* [Awesome](#awesome)
* [Books](#books)
* [Resources](#resources)
  * [Combinators](#combinators)
* [Presentations](#presentations)
* [Videos](#videos)
* [Youtube channels](#youtube-channels)
* [Libraries](#libraries)
  * [JavaScript](#javascript)
  * [LiveScript](#livescript)
  * [Java](#java)
  * [Clojure/ClojureScript](#clojureclojurescript)
  * [Scala](#scala)
  * [Kotlin](#kotlin)
  * [F#](#f)
  * [C#](#c)
  * [Swift](#swift)
  * [Python](#python)
  * [PHP](#php)
  * [Rust](#rust)
  * [Julia](#julia)
  * [Go](#go)
  * [Haskell](#haskell)
  * [Elixir](#elixir)
  * [Erlang](#erlang)
  * [OCaml](#ocaml)
  * [Racket](#racket)
* [Languages](#languages)

## Tutorials and Articles

* [Thinking in Ramda - Blog series](http://randycoulman.com/blog/categories/thinking-in-ramda/)
* [Part 1: An Intro to Functional Programming Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c)
* [Part 2: An Intro to Functional Programming Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-part-2-f45228c49eed)
* [Part 3: An Intro to Functional Programming Concepts in JavaScript](https://medium.com/@collardeau/part-3-an-intro-to-functional-programming-concepts-in-javascript-febf9368ffe6)
* [Dipping into wu.js: autoCurry](https://javascriptweblog.wordpress.com/2010/06/14/dipping-into-wu-js-autocurry)
* [Haskell in ES6: Part 1](http://casualjavascript.com/?1)
* [Haskell in ES6: Part 2](http://casualjavascript.com/?2)
* [Haskell in ES6: Project Euler 1-5](http://casualjavascript.com/?3)
* [Don’t Be Scared Of Functional Programming](http://www.smashingmagazine.com/2014/07/dont-be-scared-of-functional-programming)
* [Short cut fusion](https://wiki.haskell.org/Short_cut_fusion)
* [My favorite functional adaptors](http://glebbahmutov.com/blog/my-favorite-functional-adaptors)
* [Functional pipeline](http://glebbahmutov.com/blog/functional-pipeline)
* [Partial argument binding with heroin](http://glebbahmutov.com/blog/partial-argument-binding-with-heroin/)
* [Too much curry](http://glebbahmutov.com/blog/too-much-curry/)
* [Lodash to Ramda example](http://glebbahmutov.com/blog/lodash-to-ramda-example/)
* [Functional JavaScript interview question](http://glebbahmutov.com/blog/functional-js-interview-question/)
* [Configurable function pattern](http://glebbahmutov.com/blog/configurable-function-pattern/)
* [Combine promises with Maybe functors](http://glebbahmutov.com/blog/combine-promises-with-maybe-functors/)
* [Test if a function is pure](http://glebbahmutov.com/blog/test-if-a-function-is-pure/)
* [Functor + Applicative = Applier](http://glebbahmutov.com/blog/appliers/)
* [Point-free programming is not pointless](http://glebbahmutov.com/blog/point-free-programming-is-not-pointless/)
* [Immutable JavaScript example](http://glebbahmutov.com/blog/immutable-javascript-example/)
* [Separate work from control flow using functional programming](http://glebbahmutov.com/blog/separate-work-from-control-flow-using-functional-programming/)
* [OO vs FP console log example](http://glebbahmutov.com/blog/oo-vs-fp-log-example/)
* [Essence of functional programming](http://glebbahmutov.com/blog/essence-of-functional-programming/)
* [Adapted point-free callbacks](http://glebbahmutov.com/blog/adapted-point-free-callbacks/)
* [Counting predicates](http://glebbahmutov.com/blog/counting-predicates/)
* [Run N promises in parallel](http://glebbahmutov.com/blog/run-n-promises-in-parallel/)
* [Too much point-free](http://glebbahmutov.com/blog/too-much-point-free/)
* [Factorial using promises](http://glebbahmutov.com/blog/factorial-using-promises/)
* [Reduce reigns supreme](http://glebbahmutov.com/blog/reduce-reigns-supreme/)
* [Binding vs partial application](http://glebbahmutov.com/blog/binding-vs-partial-application/)
* [Passing multiple arguments in promises](http://glebbahmutov.com/blog/passing-multiple-arguments-in-promises/)
* [What is the difference between streams and functional reactive programming?](http://glebbahmutov.com/blog/what-is-the-difference-between-streams-and-functional-reactive-programming/)
* [Remove boilerplate from promise chains](http://glebbahmutov.com/blog/remove-boilerplate-from-promise-chains/)
* [Use JavaScript functor today](http://glebbahmutov.com/blog/use-javascript-functor-today/)
* [Heavy lifting](http://glebbahmutov.com/blog/heavy-lifting/)
* [Deep picking](http://glebbahmutov.com/blog/deep-picking/)
* [Partial application for options object](http://glebbahmutov.com/blog/partial-application-for-options-object/)
* [Unapply attack](http://glebbahmutov.com/blog/unapply-attack/)
* [Return a promise for cleaner API](http://glebbahmutov.com/blog/return-a-promise-for-cleaner-api/)
* [Imperative to compose example](http://glebbahmutov.com/blog/imperative-to-compose-example/)
* [Variable assignment shortcut](http://glebbahmutov.com/blog/variable-assignment-shortcut/)
* [Favoring Curry](http://fr.umio.us/favoring-curry)
* [The Philosophy of Ramda](http://fr.umio.us/the-philosophy-of-ramda)
* [Ranging Near and Far](http://fr.umio.us/ranging-near-and-far)
* [Iffy Literals](http://fr.umio.us/iffy-literals)
* [Why Ramda?](http://fr.umio.us/why-ramda)
* [Say "Hello" to Lo-Dash](http://kitcambridge.be/blog/say-hello-to-lo-dash)
* [Functional JavaScript using Lo-Dash, an underscore.js alternative](https://blog.codecentric.de/en/2013/01/functional-javascript-lo-dash-underscore-js-alternative)
* [Currying in JavaScript](https://medium.com/@kevincennis/currying-in-javascript-c66080543528)
* [Recursion in JavaScript](https://medium.com/@kevincennis/recursion-in-javascript-1608032c7a1f)
* [How to Speed Up Lo-Dash ×100? Introducing Lazy Evaluation](http://filimanjaro.com/blog/2014/introducing-lazy-evaluation)
* [ECMAScript 6 and Array Comprehension](http://ariya.ofilabs.com/2013/01/es6-and-array-comprehension.html)
* [Implicit Function Chaining in Lodash](https://blog.mariusschulz.com/2015/05/14/implicit-function-chains-in-lodash)
* [Lodash and ECMAScript 2015](https://blog.mariusschulz.com/2015/05/11/lodash-and-ecmascript-2015)
* [Applicative Programming In JavaScript With lodash.js](http://codylindley.com/techpro/2013_10_14__functional-javascript)
* [Better Support for Functional Programming in Angular 2](http://victorsavkin.com/post/108837493941/better-support-for-functional-programming-in)
* [16 Months of Functional Programming](http://www.vasinov.com/blog/16-months-of-functional-programming)
* [Functional UI and Components as Higher Order Functions](https://blog.risingstack.com/functional-ui-and-components-as-higher-order-functions)
* [Functional programming with Ramda](https://medium.com/@kevinle/functional-programming-with-ramda-5c56d09c518e)
* [Functional programming on frontend with React & ClojureScript](http://blog.scalac.io/2015/04/02/clojurescript-reactjs-reagent.html)
* [Functional Programming should be your #1 priority for 2015](https://medium.com/@jugoncalves/functional-programming-should-be-your-1-priority-for-2015-47dd4641d6b9)
* [Practical Functional Javascript with Ramda](http://developer.telerik.com/featured/practical-functional-javascript-ramda)
* [Streaming Logs with Transducers and Ramda](http://simplectic.com/blog/2015/ramda-transducers-logs)
* [The power of Immutability and React](https://medium.com/@sharifsbeat/the-power-of-immutability-and-react-daf46f2a5f4d)
* [Tacit Ramda](https://medium.com/@bobiblazeski/tacit-ramda-c914775ff4b1)
* [Composing Functions in JavaScript](http://blakeembrey.com/articles/2014/01/compose-functions-javascript)
* [Partial Application in JavaScript](http://blakeembrey.com/articles/2014/01/partial-application-in-javascript/)
* [Forcing Function Arity in JavaScript](http://blakeembrey.com/articles/2014/01/forcing-function-arity-in-javascript)
* [Wrapping JavaScript Functions](http://blakeembrey.com/articles/2014/01/wrapping-javascript-functions)
* [Partial Application in JavaScript](http://ejohn.org/blog/partial-functions-in-javascript)
* [Functional JavaScript](http://blog.osteele.com/posts/2007/07/functional-javascript)
* [Compiling to lambda-calculus: Turtles all the way down](http://matt.might.net/articles/compiling-up-to-lambda-calculus)
* [Point-free programming style in F#](http://www.jayway.com/2012/05/08/point-free-programming-style-in-f)
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript)
* [Partially Applied Functions In JavaScript](https://lostechies.com/derickbailey/2012/07/20/partially-applied-functions-in-javascript)
* [Neural Networks, Types, and Functional Programming](http://colah.github.io/posts/2015-09-NN-Types-FP)
* [Currying in JavaScript](https://medium.com/@kbrainwave/currying-in-javascript-ce6da2d324fe)
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps)
* [Factorial and Fibonacci in Kotlin](http://carlosqt.blogspot.com/2012/04/factorial-and-fibonacci-in-kotlin.html)
* [Functional programming with Javascript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html)
* [Элементы функциональных языков](http://fprog.ru/2009/issue3/eugene-kirpichov-elements-of-functional-languages)
* [Functional Programming should be your #1 priority for 2015 — OOP cannot save us from the Cloud Monster anymore.](https://medium.com/@jugoncalves/functional-programming-should-be-your-1-priority-for-2015-47dd4641d6b9)
* [A practical introduction to functional programming](http://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming)
* [Functional programming in R language](http://adv-r.had.co.nz/Functional-programming.html)
* [Category Theory in JavaScript](https://jscategory.wordpress.com) (must have)
* [Understanding Continuations](https://www.fpcomplete.com/user/jwiegley/understanding-continuations)
* [Tasks, microtasks, queues and schedules](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules)
* [Polyfilling generators](http://gu.illau.me/posts/polyfilling-generators)
* [Fixed-point combinators in JavaScript: Memoizing recursive functions](http://matt.might.net/articles/implementation-of-recursive-fixed-point-y-combinator-in-javascript-for-memoization)
* [Asynchronous programming and continuation-passing style in JavaScript](http://www.2ality.com/2012/06/continuation-passing-style.html)
* [By example: Continuation-passing style in JavaScript](http://matt.might.net/articles/by-example-continuation-passing-style)
* [The Y Combinator (Slight Return)](http://mvanier.livejournal.com/2897.html)
* [Leaking Space - Eliminating memory hogs](https://queue.acm.org/detail.cfm?id=2538488)
* [Breaking down FRP](https://blogs.janestreet.com/breaking-down-frp)
* [What are some limitations/disadvantages of functional programming?](https://www.quora.com/What-are-some-limitations-disadvantages-of-functional-programming)
* [Fun with promises in JavaScript](https://www.stephanboyer.com/post/107/fun-with-promises-in-javascript)
* [Getting clever with lambda calculus](http://casualjavascript.com/2015/12/18/getting-clever-with-lambda.html)
* [Servant, Type Families, and Type-level Everything A look at advanced GHC features used in Servant](http://www.arow.info/blog/posts/2015-07-10-servant-intro.html)
* [Haskell-Style Fibonacci in Python](http://joelgrus.com/2015/07/07/haskell-style-fibonacci-in-python/)
* [Polyglot Twitter Bot, Part 1: Node.js](http://joelgrus.com/2015/12/29/polyglot-twitter-bot-part-1-nodejs/)
* [Polyglot Twitter Bot, Part 2: Node.js + AWS Lambda](http://joelgrus.com/2015/12/29/polyglot-twitter-bot-part-2-nodejs-aws-lambda/)
* [Polyglot Twitter Bot, Part 3: Python 2.7 + AWS Lambda](http://joelgrus.com/2015/12/30/polyglot-twitter-bot-part-3-python-27-aws-lambda/)
* [Functional programming with Ramda.js](http://neiro.io/2015/09/05/functional-programming-with-ramda-js.html)
* [The Little Idea of Functional Programming](http://jaysoo.ca/2016/01/13/functional-programming-little-ideas)
* [What is a functor?](https://medium.com/@dtinth/what-is-a-functor-dcf510b098b6#.zf6crffs6)
* [What Is Functional Programming?](http://blog.jenkster.com/2015/12/what-is-functional-programming.html)
* [Which Programming Languages Are Functional?](http://blog.jenkster.com/2015/12/which-programming-languages-are-functional.html)
* [An Introduction to Functional Programming in JavaScript](https://bjpelc.wordpress.com/2015/02/06/an-introduction-to-functional-programming-in-javascript)
* [Input and Output](http://learnyouahaskell.com/input-and-output)
* [Function Application and Definition](http://slpopejoy.github.io/posts/2014-11-27-FunctionApplicationDefinition.html)
* [Types & Kinds](http://slpopejoy.github.io/posts/2015-04-10-Types.html)
* [Effectful Haskell: Reader, Transformers, Typeclasses](http://slpopejoy.github.io/posts/Effectful02.html)
* [asynquence: The Promises You Don’t Know Yet (Part 1)](https://davidwalsh.name/asynquence-part-1)
* [asynquence: More Than Just Promises (Part 2)](https://davidwalsh.name/asynquence-part-2)
* [Going Async With ES6 Generators](https://davidwalsh.name/async-generators)
* [Getting Concurrent With ES6 Generators](https://davidwalsh.name/concurrent-generators)
* [Currying versus partial application (with JavaScript code)](http://www.2ality.com/2011/09/currying-vs-part-eval.html)
* [Flatmap explained](https://porizi.wordpress.com/2014/02/21/flatmap-explained)
* [Applicatives are generalized functors](https://hseeberger.wordpress.com/2011/01/31/applicatives-are-generalized-functors)
* [Introduction to Category Theory in Scala](https://hseeberger.wordpress.com/category/category-theory)
* [Understanding Transducers](http://elbenshira.com/blog/understanding-transducers)
* [Understanding Transducers in JavaScript](https://medium.com/@roman01la/understanding-transducers-in-javascript-3500d3bd9624#.ze7jh4h2x)
* [Visualizing Concurrency in Go](https://divan.github.io/posts/go_concurrency_visualize)
* [Lazy Iterables in JavaScript](http://raganwald.com/2015/02/17/lazy-iteratables-in-javascript.html)
* [Difference between a Promise and a Task](https://glebbahmutov.com/blog/difference-between-promise-and-task)
* [Switching from immutable.js to seamless-immutable](http://tech.noredink.com/post/107617838018/switching-from-immutablejs-to-seamless-immutable)
* [A Gentle Introduction to Functional JavaScript: Part 1](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro)
* [A Gentle Introduction to Functional JavaScript: Part 2](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-arrays)
* [A Gentle Introduction to Functional JavaScript: Part 3](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-functions)
* [A Gentle Introduction to Functional JavaScript: Part 4](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-style)
* [From mathematics to map-reduce](http://www.haskellforall.com/2016/02/from-mathematics-to-map-reduce.html)
* [Continuations](https://curiosity-driven.org/continuations)
* [Elmish: Functional Programming in Javascript](https://medium.com/@chetcorcos/elmish-functional-programming-in-javascript-50995f1d4b9e#.gxfuglcw8)
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504#.65dy1pg1i)
* [Coroutine Event Loops in Javascript](https://x.st/javascript-coroutines)
* [How Do I Learn Functional Programming In Javascript? - Linkpost](http://www.fse.guru/how-do-i-learn-functional-programming-in-javascript-linkpost)
* [Debugging Functional](https://medium.com/@drboolean/debugging-functional-7deb4688a08c#.bbrftrszz)
* [Why using `_.chain` is a mistake](https://medium.com/making-internets/why-using-chain-is-a-mistake-9bc1f80d51ba#.hq00cmdrw)
* [More points for lazy evaluation](http://augustss.blogspot.com/2011/05/more-points-for-lazy-evaluation-in.html)
* [Trampolines in JavaScript](http://raganwald.com/2013/03/28/trampolines-in-javascript.html)
* [Where combinator names come from](http://www.johndcook.com/blog/2014/02/06/schonfinkel-combinators/)
* [Category Theory for Promises/A+](https://brianmckenna.org/blog/category_theory_promisesaplus)
* [Everything Reduced: Transducers in Javascript](https://medium.com/@dtipson/everything-reduced-transducers-in-javascript-8ea3459bc7f9#.8udfq9qgc)
* [Javascript Transducers 2: Stateful & Gateful](https://medium.com/@dtipson/javascript-transducers-2-stateful-gateful-1faa1b01ae50#.tpd0umbp2)
* [Creating an ES6ish Compose in Javascript](https://medium.com/@dtipson/creating-an-es6ish-compose-in-javascript-ac580b95104a#.iiyge32r2)
* [More Functional Javascript: Reducing Promises, Ramda.js, & Arrow functions again](https://medium.com/@dtipson/more-functional-javascript-reducing-promises-ramda-js-arrow-functions-again-c1f90e0a79d0#.iazm515xv)
* [Functional Programming is for Dummies](https://medium.com/@dtipson/functional-programming-is-for-dummies-fa130a629250#.3eb04lfbp)
* [Functional Programming Principles in Scala](http://vasnake.blogspot.com/2016/03/functional-programming-principles-in.html)
* [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/2016/03/23/intro-to-immutable-js/)
* [Functional Programming in JavaScript - The Functional Paradigm in a Familiar Language](https://dzone.com/refcardz/functional-programming-with-javascript)
* [Using Lodash as a Collection of Micro-Libraries](http://knpw.rs/blog/using-lodash)
* [See How Easily You Can Create a Promise](https://o2js.com/see-how-easily-you-can-create-a-promise)
* [Achieving point-free JavaScript with R.converge / \_.over](https://medium.com/@nicoespeon/achieving-point-free-javascript-with-r-converge-overargs-94060fd0ed7a#.xi63eq605)
* [Introduction to Functional JavaScript](https://medium.com/functional-javascript/introduction-to-functional-javascript-45a9dca6c64a#.pofkvcd7z)
* [Functions](https://medium.com/functional-javascript/functions-61b9096b5638#.6ntr05g4z)
* [Higher Order Functions](https://medium.com/functional-javascript/higher-order-functions-78084829fff4#.inii2wlzh)
* [Recursion](https://medium.com/functional-javascript/recursion-282a6abbf3c5#.4x0h9awy7)
* [3. More Functional Swift](https://medium.com/swift-programming/3-more-functional-swift-4bb7256c087d#.odesvmw2c)
* [2. Functional Swift](https://medium.com/swift-programming/2-functional-swift-c98be9533183#.ze1gph6zi)
* [Swift closures and functions](http://fuckingswiftblocksyntax.com/)
* [Debouncing and Throttling Explained Through Examples](https://css-tricks.com/debouncing-throttling-explained-examples/)
* [Foldable and Traversable](http://blog.jakubarnold.cz/2014/07/30/foldable-and-traversable.html)
* [How do Promises Work?](http://robotlolita.me/2015/11/15/how-do-promises-work.html)
* [Javascript generators and functional reactive programming](http://sitr.us/2014/08/02/javascript-generators-and-functional-reactive-programming.html)\\
* [No promises: asynchronous JavaScript with only generators](http://www.2ality.com/2015/03/no-promises.html)
* [Functional Mixins in ECMAScript 2015](http://raganwald.com/2015/06/17/functional-mixins.html)
* [CSP and transducers in JavaScript](http://phuu.net/2014/08/31/csp-and-transducers.html)
* [ES6 generators in depth](http://www.2ality.com/2015/03/es6-generators.html)
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504#.teglaxq5d)
* [The allure of Scala.js](http://blog.ramnivas.com/technology/2016/02/09/the-allure-of-scalajs.html)
* [Swift Guide to Map Filter Reduce](http://useyourloaf.com/blog/swift-guide-to-map-filter-reduce/)
* [6 Reasons Why You Should Write Functional Code](http://funkyjavascript.com/6-reasons-why-you-should-write-functional-code/)
* [The Perfect API](http://james-forbes.com/?/posts/the-perfect-api)
* [(Basic) Lazy Evaluation and Memoization in JavaScript](http://blog.gypsydave5.com/2015/03/21/lazy-eval-and-memo/)
* [Divide and Conquer with Algebraic Structures](https://medium.com/@drboolean/divide-and-conquer-with-algebraic-structures-14070106fb4#.ae1a9xf08)
* [Async and await](https://zeit.co/blog/async-and-await)
* [Applicative functors: definition and syntax](http://tomasp.net/blog/applicative-functors.aspx/)
* [Proofs of functor laws in Haskell](http://ssomayyajula.github.io/posts/2015-11-07-proofs-of-functor-laws-with-Haskell.html)
* [The functor design pattern](http://www.haskellforall.com/2012/09/the-functor-design-pattern.html)
* [A 𝝺-CALCULUS INTERPRETER - in less than 200 lines of JavaScript](http://tadeuzagallo.com/blog/writing-a-lambda-calculus-interpreter-in-javascript/)
* [Tree traversal in CoffeeScript](https://alisdair.mcdiarmid.org/tree-traversal-in-coffeescript/)
* [Monoidal Contravariant Functors are actually useful!](https://medium.com/@drboolean/monoidal-contravariant-functors-are-actually-useful-1032211045c4#.pmf31o9gd)
* [Infinite collections with ES6 generators](https://advancedweb.hu/2016/05/31/infinite-collections-with-es6-generators/)
* [Improving your functional CoffeeScript and JavaScript](https://www.jayway.com/2013/12/22/improving-your-functional-coffeescript-and-javascript/)
* [Comparing Javascript generators vs Clojurescript lazy-seq by solving a Fibonnaci problem](https://medium.com/@rlucha/comparing-javascript-generators-vs-clojurescript-lazy-seq-by-solving-a-fibonnaci-problem-61c1524d67d6#.swxk99bgd)
* [Grasping Haskell: functors, applicatives and monads (part 1)](https://medium.com/@xanderdeseyn/grasping-haskell-functors-applicatives-and-monads-part-1-93368e0a7a74#.692ooxhnz)
* [Grasping Haskell: functors, applicatives and monads (part 2)](https://medium.com/@xanderdeseyn/grasping-haskell-functors-applicatives-and-monads-part-2-65255e3e6a1d#.xigtg4wma)
* [Functor, Foldable, and Traversable Over Binary Tree](https://queertypes.com/posts/37-functor-traverse-fold-tree.html)
* [Functional Components with React stateless functions and Ramda](https://medium.com/@mirkomariani/functional-components-with-react-stateless-functions-and-ramda-e83e54fcd86b#.tr2jf6dv6)
* [Support for deriving Functor, Foldable, and Traversable instances](https://ghc.haskell.org/trac/ghc/wiki/Commentary/Compiler/DeriveFunctor)
* [Fold (higher-order function)](https://en.wikipedia.org/wiki/Fold_\(higher-order_function\))
* [Making a Haskell (Scotty) web app and putting it on Heroku](http://qiita.com/kimagure/items/5947e2db40b9ec2226bf)
* [Promises + FP = Beautiful Streams](https://medium.com/@yelouafi/promises-fp-beautiful-streams-6f0235c5b179#.fl8mmu2xs)
* [Composability: from Callbacks to Categories in ES6](https://medium.com/@homam/composability-from-callbacks-to-categories-in-es6-f3d91e62451e#.x3q3q9pzl)
* [Understanding F-Algebras](https://www.schoolofhaskell.com/user/bartosz/understanding-algebras)
* [Fold](https://wiki.haskell.org/Fold)
* [Why Functional Programming Matters](https://blog.acolyer.org/2016/09/14/why-functional-programming-matters/)
* [Smarter validation](https://ro-che.info/articles/2015-05-02-smarter-validation)
* [The Algebra of Algebraic Data Types, Part 1](http://chris-taylor.github.io/blog/2013/02/10/the-algebra-of-algebraic-data-types/)
* [The Algebra of Algebraic Data Types, Part 2](http://chris-taylor.github.io/blog/2013/02/11/the-algebra-of-algebraic-data-types-part-ii/)
* [The Algebra of Algebraic Data Types, Part 3](http://chris-taylor.github.io/blog/2013/02/13/the-algebra-of-algebraic-data-types-part-iii/)
* [Async in Purescript is fun and easy](http://qiita.com/kimagure/items/2ebce1399bac00c79656)
* [Design Patterns in Haskell](http://blog.ezyang.com/2010/05/design-patterns-in-haskel/)
* [So You Want to be a Functional Programmer Series by Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536#.cxfubzoqh)
* [Haskell Progressive Example - An OpenGL 3D extension of the Mandelbrot set](http://yannesposito.com/Scratch/en/blog/Haskell-OpenGL-Mandelbrot/)
* [Folds and Infinite Lists](http://argumatronic.com/posts/2016-09-17-infinite-folds.html)
* [list-transformer - A beginner-friendly ListT](http://www.haskellforall.com/2016/07/list-transformer-beginner-friendly-listt.html)
* [Sharing, Space Leaks, and Conduit and friends](http://www.well-typed.com/blog/2016/09/sharing-conduit/)
* [Functors are Containers](https://bartoszmilewski.com/2014/01/14/functors-are-containers/)
* [Tuples in JavaScript](http://oli.me.uk/2013/07/12/tuples-in-javascript/)
* [Making juice with reduce/foldl](http://www.macwright.org/2015/01/03/reduce-juice.html)
* [Getting audio from Youtube channels in the easiest way possible using Haskell](http://qiita.com/kimagure/items/0a2f3d60789c646e4426)
* [From Callback to Future -> Functor -> Monad](https://hackernoon.com/from-callback-to-future-functor-monad-6c86d9c16cb5)
* [Slaying a UI Antipattern in Fantasyland](https://medium.com/javascript-inside/slaying-a-ui-antipattern-in-fantasyland-907cbc322d2a#.rmepdr82j)
* [Form Validation As A Higher Order Component Pt.1](https://medium.com/javascript-inside/form-validation-as-a-higher-order-component-pt-1-83ac8fd6c1f0#.u2pkcyfb6)
* [Form Validation As A Higher Order Component Pt.2](https://medium.com/javascript-inside/form-validation-as-a-higher-order-component-pt-2-1edb7881870d#.ldwpp7qgl)
* [Using JavaScript to Learn Haskell](https://medium.com/@sjsyrek/using-javascript-to-learn-haskell-f57509015842#.g5kbyrz77)
* [FFI with Haskell and Rust](https://mgattozzi.github.io/2016/10/01/haskell-rust.html)
* [A Taste of Haskell](https://hookrace.net/blog/a-taste-of-haskell/)
* [BEAUTIFUL FOLDS IN SCALA](https://softwaremill.com/beautiful-folds-in-scala/)
* [Functional Programming In JS — With Practical Examples (Part 1)](https://medium.com/@rajaraodv/functional-programming-in-js-with-practical-examples-part-1-87c2b0dbc276#.y01dinh7e)
* [Immutable.js: The True Joy of JavaScript](http://blog.sigmapoint.pl/immutable-js-the-true-joy-of-javascript/)
* [Mutual Recursion in Final Encoding](https://aherrmann.github.io/programming/2016/05/28/mutual-recursion-in-final-encoding/)
* [Semigroups](https://medium.com/@gcanti/semigroups-f74f7643c0d4#.okttdogyg)
* [Using F# on both the frontend and the backend](http://danielbachler.de/2016/12/10/f-sharp-on-the-frontend-and-the-backend.html)
* [Stack safe Function composition](https://medium.com/@safareli/stack-safe-function-composition-85d61feee37e#.fige7eu8l)
* [Applicative functors: definition and syntax](http://tomasp.net/blog/applicative-functors.aspx/)
* [The versatility of Array methods](https://james-forbes.com/index.html?/posts/versatility-of-array-methods)
* [Functional Programming in JavaScript](http://dealwithjs.io/functional-programming-in-javascript/)
* [Abstracting Computations with Type Classes](https://freecontent.manning.com/abstracting-computations-with-type-classes/)

### [Lenses]()

* [Lenses In Pictures](http://adit.io/posts/2013-07-22-lenses-in-pictures.html)
* [Lenses and Virtual DOM Support Open Closed](http://joneshf.github.io/programming/2015/12/19/Lenses-and-Virtual-DOM-Support-Open-Closed.html)
* [JavaScript through the Lenses of Functional Programming](https://web.archive.org/web/20160802064916/http://www.luisatencio.net/2015/09/javascript-through-lenses-of-functional.html)
* [How functional programming lenses work](http://fluffynukeit.com/how-functional-programming-lenses-work)
* [Basic Lensing](https://www.schoolofhaskell.com/school/to-infinity-and-beyond/pick-of-the-week/basic-lensing)
* [Lenses with Immutable.js](https://medium.com/@drboolean/lenses-with-immutable-js-9bda85674780#.hwrcbhxyu)
* [Использование линз на реальных примерах](http://blog.csssr.ru/2016/07/08/lenses/)
* [lens over tea #1: lenses 101, traversals 101, and some implementation details](https://artyom.me/lens-over-tea-1)
* [Functional Lenses, How Do They Work](https://medium.com/@dtipson/functional-lenses-d1aba9e52254#.6hlng669r)
* [An Introduction Into Lenses In JavaScript Functional Getter/Setter](https://medium.com/javascript-inside/an-introduction-into-lenses-in-javascript-e494948d1ea5#.ck7t1syp0)
* [Pointwise Lenses](https://www.well-typed.com/blog/2014/04/pointwise-lenses/)
* [Линзы: Real World](https://ruhaskell.org/posts/packages/2015/01/28/lenses-real-world.html)
* [Haskell Lenses Notes](https://rafal.io/posts/haskell-lenses-notes.html)
* [Isomorphism lenses](http://www.twanvl.nl/blog/haskell/isomorphism-lenses)
* [An Intro to Lens With No Theory](https://abesto.net/an-intro-to-lens-with-no-theory/)
* [Lens you an applicative for great haskell?](https://izbicki.me/blog/lens-you-an-applicative-for-great-haskell.html)
* [I got lenses in my Functors](https://izbicki.me/blog/i-got-lenses-in-my-functors)
* [A Little Lens Starter Tutorial](https://www.schoolofhaskell.com/school/to-infinity-and-beyond/pick-of-the-week/a-little-lens-starter-tutorial)
* [Introduction to optics: lenses and prisms](https://medium.com/@gcanti/introduction-to-optics-lenses-and-prisms-3230e73bfcfe#.nnp002k5j)
* [Lens Tutorial - Introduction (part 1)](http://blog.jakubarnold.cz/2014/07/14/lens-tutorial-introduction-part-1.html)
* [Lens Tutorial - Stab & Traversal (Part 2)](http://blog.jakubarnold.cz/2014/08/06/lens-tutorial-stab-traversal-part-2.html)

### [Monads](https://en.wikipedia.org/wiki/Monad_\(functional_programming\))

* [Monads: Your App as a Function, Part 1](http://mttkay.github.io/blog/2014/01/25/your-app-as-a-function)
* [Monads: Your App as a Function, Part 2](https://mttkay.github.io/blog/2014/01/25/monads-your-app-as-a-function-part-2)
* [The Marvels of Monads](http://blogs.msdn.com/b/wesdyer/archive/2008/01/11/the-marvels-of-monads.aspx)
* [A Fistful of Monads](http://learnyouahaskell.com/a-fistful-of-monads)
* [Category Theory via C# (22) More Monad: Continuation Monad](http://weblogs.asp.net/dixin/category-theory-via-c-sharp-22-more-monad-continuation-monad)
* [The Mother of all Monads](http://blog.sigfpe.com/2008/12/mother-of-all-monads.html)
* [Understanding Monads With JavaScript](http://igstan.ro/posts/2011-05-02-understanding-monads-with-javascript.html)
* [Promises are the monad of asynchronous programming](https://blog.jcoglan.com/2011/03/11/promises-are-the-monad-of-asynchronous-programming)
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html)
* [A Monad in Practicality: Controlling Time](http://robotlolita.me/2014/03/20/a-monad-in-practicality-controlling-time.html)
* [Monads in JavaScript](https://curiosity-driven.org/monads-in-javascript)
* [Mindfuck: The Reverse State Monad](https://lukepalmer.wordpress.com/2008/08/10/mindfuck-the-reverse-state-monad)
* [Comonads, Monoids and Trees](http://joneshf.github.io/programming/2015/12/31/Comonads-Monoids-and-Trees.html) (awesome article)
* [The Delimited Continuation Monad in Javascript](http://blog.mattbierner.com/the-delimited-continuation-monad-in-javascript)
* [Free Monads Are Simple](http://underscore.io/blog/posts/2015/04/14/free-monads-are-simple.html)
* [Effectful Haskell: IO, Monads, Functors](http://slpopejoy.github.io/posts/Effectful01.html)
* [Functors, Applicative Functors, and Monads aren't that scary](http://gabrielsw.blogspot.com/2011/08/functors-applicative-functors-and.html)
* [Functors, Monads, Applicatives – can be so simple](https://thedet.wordpress.com/2012/04/28/functors-monads-applicatives-can-be-so-simple)
* [Practical Intro to Monads in JavaScript](http://tech.evojam.com/2016/02/22/practical-intro-to-monads-in-javascript)
* [The Indexed State Monad in Haskell, Scala, and C#](https://gist.github.com/pthariensflame/5054294)
* [Who in Their Right Mind Would Use Monads in Clojure?](http://blog.muhuk.com/2015/10/01/who_in_their_right_mind_would_use_monads_in_clojure.html#.VuvdlJN97PB)
* [Let’s Make a Monad](https://medium.com/@dtipson/hey-let-s-make-a-monad-e276802fdb0c#.2wbev1dme)
* [Let’s Put jQuery in a Monad](https://medium.com/@dtipson/let-s-make-jquery-a-monad-7df0e79a842d#.bq9lz9fm7)
* [Monads in C++](http://bartoszmilewski.com/2011/07/11/monads-in-c/)
* [Monads in plain JavaScript](http://modernjavascript.blogspot.com/2013/06/monads-in-plain-javascript.html)
* [Practical Intro to Monads in JavaScript: Either](https://tech.evojam.com/2016/03/21/practical-intro-to-monads-in-javascript-either)
* [Practical Intro to Monads in JavaScript: Validation](https://tech.evojam.com/2016/04/26/practical-intro-to-monads-in-javascript-validation/)
* [Practical Intro to Monads in JavaScript](https://tech.evojam.com/2016/02/22/practical-intro-to-monads-in-javascript/)
* [Monads, promises, arrays in Javascript](http://pseudocorta.blogspot.com/2014/05/monads-promises-arrays-in-javascript.html)
* [Monad syntax for JavaScript](https://blog.jcoglan.com/2011/03/06/monad-syntax-for-javascript)
* [Translation from Haskell to JavaScript of selected portions of the best introduction to monads I’ve ever read](https://blog.jcoglan.com/2011/03/05/translation-from-haskell-to-javascript-of-selected-portions-of-the-best-introduction-to-monads-ive-ever-read)
* [Monads](http://functionaljavascript.blogspot.com/2013/07/monads.html)
* [A Gentle Intro to Monads … Maybe?](http://sean.voisen.org/blog/2013/10/intro-monads-maybe)
* [Monads - function composition on steroids](http://pkaczor.blogspot.com/2013/09/monads-function-composition-on-steroids.html)
* [Rx for Haskell - My First Monad](http://haskellrescue.blogspot.com/2011/06/rx-for-haskell-my-first-monad.html)
* [Monads for Dummies](http://jabberwocky.eu/2012/11/02/monads-for-dummies/)
* [Week 3 - Introduction to Monads in JavaScript](http://www.aaronhsmith.com/2015/09/08/introduction-monads-javascript/)
* [Монады в Javascript](http://kolesnichenkods.github.io/2015/08/01/%D0%9C%D0%BE%D0%BD%D0%B0%D0%B4%D1%8B-%D0%B2-JavaScript/)
* [Аналоги монад Haskell](http://www.linux.org.ru/forum/development/7730147)
* [Functors, Applicatives, and Monads in Plain English](http://www.russbishop.net/monoids-monads-and-functors)
* [what does “lifting” mean?](http://cstheory.stackexchange.com/questions/14125/what-does-lifting-mean/14126#14126)
* [Free and Freer Monads: Putting Monads Back into Closet](http://okmij.org/ftp/Computation/free-monad.html)
* [Akh - Monad Transformers for Javascript](http://blog.mattbierner.com/akh-monad-transformers-for-javascript/)
* [Decision Trees Are Free Monads Over the Reader Functor](http://clathomasprime.github.io/hask/freeDecision)
* [Собираемся с духом и перестаем бояться монад](http://eax.me/monads/)
* [Утилиты работы с монадами](http://www.haskell.ru/monad.html)
* [Ru/IO Inside](https://wiki.haskell.org/Ru/IO_Inside)
* [Foldable.mapM\_, Maybe, and recursive functions](https://www.schoolofhaskell.com/user/snoyberg/general-haskell/basics/foldable-mapm-maybe-and-recursive-functions#mono-traversable)
* [Of Algebirds, Monoids, Monads, and Other Bestiary for Large-Scale Data Analytics](http://www.michael-noll.com/blog/2013/12/02/twitter-algebird-monoid-monad-for-large-scala-data-analytics/#the-tldr-version-of-monoids-and-monads)
* [Comonads as Spaces](http://blog.functorial.com/posts/2016-08-07-Comonads-As-Spaces.html)
* [MonadFix](https://wiki.haskell.org/MonadFix)
* [Monads - Array, Promise and Maybe monads. Plus Docker is a functor](https://glebbahmutov.com/blog/monads/)
* [The Marvellously Mysterious JavaScript Maybe Monad](http://jrsinclair.com/articles/2016/marvellously-mysterious-javascript-maybe-monad/)
* [The midnight Monad, a journey to enlightenment](http://www.lambdacat.com/the-midnight-monad-a-journey-to-enlightenment/)
* [Monads in Haskell: ((->) r)](http://www.mjoldfield.com/atelier/2014/07/monads-fn.html)
* [Monoids, Functors, Applicatives, and Monads: 10 Main Ideas](https://monadmadness.wordpress.com/2015/01/02/monoids-functors-applicatives-and-monads-10-main-ideas/)
* [Kleisli Functors](http://elvishjerricco.github.io/2016/10/12/kleisli-functors.html)
* [The Dead Simple, No Chit Chat, Zero-Analogy Haskell Monad Tutorial](https://unknownparallel.wordpress.com/zero-analogy-monad-tutorial/)
* [Monads Demystified](http://blog.reverberate.org/2015/08/monads-demystified.html)
* [Understanding Monads](https://medium.com/real-world-fsharp/understanding-monads-db30eeadf2bf#.dtr6wmvyc)
* [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)
* [Monads as Practical Functionality Providers](https://freecontent.manning.com/monads-as-practical-functionality-providers/)

### [Purescript](http://www.purescript.org)

* [Building Apps with PureScript and React](https://kritzcreek.github.io/tutorial/2015/03/31/apps-with-purescript-and-react-1)
* [Frontend Functional Programming with PureScript and Elm](http://blog.thomasstreet.com/post/129725260288/frontend-functional-programming-with-purescript)
* [Writing PureScript Bindings for a jQuery Plugin](https://filib.io/posts/2015-11-06-writing-purescript-bindings-for-a-jquery-plugin.html)
* [PureScript on Android](http://blog.ndk.io/purescript-on-android.html)
* [Rendering a Tic-Tac-Toe board with purescript-react](https://kritzcreek.github.io/example/2015/10/03/tic-tac-toe-with-purescript)
* [Playing Tic-Tac-Toe using purescript-signal](https://kritzcreek.github.io/tutorial/2015/10/07/playing-tic-tac-toe-with-purescript-signal)
* [Fighting node callback hell with PureScript](https://andreypopp.com/posts/2014-07-21-fighting-node-callbacks-with-purescript.html)
* [Approximating PI With PureScript](http://sleepomeno.github.io/blog/2015/03/14/Approximating-PI-with-PureScript/)
* [Learn X in Y minutes - Where X=purescript](https://learnxinyminutes.com/docs/purescript/)
* [PureScript for the Haskeller Where to get started in PureScript for the Haskell programmer](http://www.arow.info/blog/posts/2015-12-17-purescript-intro.html)
* [Polyglot Twitter Bot, Part 4: PureScript](http://joelgrus.com/2015/12/31/polyglot-twitter-bot-part-4-purescript/)
* [WebApps with PureScript and RactiveJS](http://blog.brakmic.com/webapps-with-purescript-and-ractivejs)
* [Managing Application State with PureScript & Redux](http://blog.brakmic.com/managing-application-state-with-purescript-redux)
* [PureScript with Leaflet Experiments](http://odoe.net/blog/purescript-with-leaflet-experiments)
* [Purescript will make you purr like a kitten](http://blog.sigmapoint.pl/purescript-will-make-you-purr-like-a-kitten)
* [PureScript + React + Electron](http://alexey.raga.name/posts/2015/09/28/purescript-react-electron)
* [Getting started in PureScript (Part 1)](https://pierrebeaucamp.surge.sh/post/Getting%20started%20in%20PureScript%20\(Part%201\))
* [Getting Started with Purescript for Web Development](http://curtis.io/purescript-for-web-development)
* [PureScript for Front End Developers](http://konkle.us/purescript-for-front-end-developers/)
* [A Real-World PureScript FE Build Setup](http://konkle.us/a-real-world-purescript-build-setup/)
* [Making a simple node program with Purescript](http://qiita.com/kimagure/items/5674e3ae9c87262af762)
* [PureScript — An Intro for JavaScript Hackers](https://medium.com/@dum.constantin/purescript-an-intro-for-javascript-hackers-605442e963a3#.h6b0uufdg)
* [Parsing complex foreign objects in PureScript](http://codingstruggles.com/purescript/purescript-parsing-complex-foreign-objects.html)
* [Writing a simple Telegram chat bot in Purescript](http://qiita.com/kimagure/items/2da0fe86b218b3f832d0)
* [Making a Weather Telegram bot in Purescript](http://futurice.com/blog/making-a-weather-telegram-bot-in-purescript)
* [Row span with PureScript pux and JavaScript redux](http://www.andrevdm.com/posts/2016-09-01-rowSpan-pux-redux.html)
* [Make the Leap from JavaScript to PureScript](https://hackernoon.com/make-the-leap-from-javascript-to-purescript-5b35b1c06fef)

### [Elm](http://elm-lang.org)

* [Building a Live-Validated Signup Form in Elm](http://tech.noredink.com/post/129641182738/building-a-live-validated-signup-form-in-elm)
* [Data Structures in Elm](http://tech.noredink.com/post/140646140878/data-structures-in-elm)
* [Walkthrough: Introducing Elm to a JS Web App](http://tech.noredink.com/post/126978281075/walkthrough-introducing-elm-to-a-js-web-app)
* [Static site generation in Elm](http://tech.noredink.com/post/140291903568/static-site-generation-in-elm)
* [Архитектура приложения в Elm](http://ruhaskell.org/posts/elm/2015/03/06/elm-architecture.html)
* [Начало проекта на Elm](http://ruhaskell.org/posts/elm/2015/01/22/elm-hello.html)
* [Optimistic UI and Reactive Programming with Elm](http://athiemann.net/2015/07/26/optimistic-ui-elm.html)
* [Understanding Signal.forwardTo](http://zkessin.github.io/elm-examples-blog//examples/2016/01/07/understanding-Signal.forwardTo.html)
* [Learning FP the hard way: Experiences on the Elm language](https://gist.github.com/ohanhi/0d3d83cf3f0d7bbea9db)
* [Architecture in Elm](https://gist.github.com/evancz/2b2ba366cae1887fe621)
* [Switching from imperative to functional programming with games in Elm](https://github.com/Dobiasd/articles/blob/master/switching_from_imperative_to_functional_programming_with_games_in_Elm.md) ⭐ 1,587 | 🐛 0 | 🌐 Python | 📅 2026-01-01
* [How Elm made our work better](http://futurice.com/blog/elm-in-the-real-world)
* [Elm for the Frontend, Right Now](https://bendyworks.com/elm-frontend-right-now)
* [Introduction to ML in Elm](https://www.classes.cs.uchicago.edu/archive/2015/winter/22300-1/lectures/IntroML.html)
* [Making a scroll table with Elm](http://qiita.com/kimagure/items/57cdd08bdf56cc51d294)
* [A simple introduction to using Elm ports](http://qiita.com/kimagure/items/f15bff4f33a63ba03877)
* [How I wrote a hybrid Elm/Javascript Node.js application](http://qiita.com/kimagure/items/da2100328aa94a736559)
* [Getting Started with Elm](https://medium.com/@diamondgfx/getting-started-with-elm-11d7a53b1a78#.xbf1ghjft)
* [Understanding Elm: Signals, Mailboxes, Addresses, and Actions](https://medium.com/@diamondgfx/understanding-elm-signals-mailboxes-addresses-and-actions-7932781396ef#.tq036zcnr)
* [Using Mailboxes in Elm](https://gist.github.com/mgold/461dbf37d4d34767e5da)
* [Developing Games In Elm - Signals](http://gelatindesign.co.uk/developing-games-in-elm/signals)
* [Signals in Elm](http://danielbachler.de/2016/02/12/signals-in-elm.html)
* [Elm by Example: Soup to Nuts - Part 1](https://hashrocket.com/blog/posts/elm-by-example-soup-to-nuts-part-1)
* [An Opening Example of Elm: building HTML by parsing parameters](http://blog.jessitron.com/2015/08/an-elm-example-reading-url-parameters.html)
* [Real World Elm - Part 2 - Form Validation](http://engineering.truqu.com/2015/09/25/real-world-elm-part-2.html)
* [Real World Elm - Part 1](http://engineering.truqu.com/2015/08/19/real-world-elm-part-1.html)
* [Deconstructing Your First Elm App](https://yobriefca.se/blog/2015/08/02/deconstructing-your-first-elm-app)
* [Introduction to FRP in Elm](https://www.classes.cs.uchicago.edu/archive/2015/winter/22300-1/lectures/IntroFRP.html)
* [Tasks and Effects in Elm](http://danielbachler.de/2016/02/19/tasks-and-effects-in-elm.html)
* [Elm Native UI: Writing a React Native app in Elm](http://ohanhi.github.io/elm-native-ui.html)
* [Learn X in Y minutes - Where X=Elm](https://learnxinyminutes.com/docs/elm)
* [A Concise Introduction to Elm](https://www.cis.upenn.edu/~matuszek/Concise%20Guides/Concise%20Elm.html)
* [Elm by Example: Soup to Nuts - Part 1](https://hashrocket.com/blog/posts/elm-by-example-soup-to-nuts-part-1)
* [Structured TodoMVC example with Elm](https://medium.com/@_rchaves_/structured-todomvc-example-with-elm-a68d87cd38da#.srxm7txdt)
* [10 reasons why you should give Elm a try](https://medium.com/@tibastral/10-reasons-why-you-should-give-elm-a-try-62b56d305643#.np2phq2v9)
* [Why Elm is Going to Change the World](https://medium.com/@dailydrip/why-elm-is-going-to-change-the-world-f5a6c693b2ca#.8hcwvohtp)
* [Building A React/Redux/Elm Bridge](https://medium.com/javascript-inside/building-a-react-redux-elm-bridge-8f5b875a9b76#.h6rmwevj4)
* [Elm for the Frontend, Right Now (Updated for Elm 0.18)](http://bendyworks.com/blog/elm-frontend-right-now-updated-for-0-18)

***

## Awesome

* [Awesome Elixir - A curated list of amazingly awesome Elixir and Erlang libraries, resources and shiny things](https://github.com/h4cc/awesome-elixir) ⭐ 13,160 | 🐛 27 | 🌐 Elixir | 📅 2025-10-12
* [Awesome Scala - A community driven list of useful Scala libraries, frameworks and software](https://github.com/lauris/awesome-scala) ⭐ 9,234 | 🐛 13 | 🌐 Python | 📅 2024-09-20
* [Awesome Elm - A curated list of useful Elm tutorials, libraries and software. Inspired by awesome list](https://github.com/isRuslan/awesome-elm) ⭐ 3,685 | 🐛 3 | 📅 2026-07-21
* [Awesome Haskell - A collection of awesome Haskell links, frameworks, libraries and software. Inspired by awesome projects line](https://github.com/krispo/awesome-haskell) ⭐ 3,284 | 🐛 17 | 🌐 Python | 📅 2026-08-03
* [Awesome Clojure - A curated list of awesome Clojure libraries and resources](https://github.com/razum2um/awesome-clojure) ⭐ 2,839 | 🐛 0 | 🌐 Clojure | 📅 2026-08-06
* [Awesome Functional Python - A curated list of awesome things related to functional programming in Python](https://github.com/sfermigier/awesome-functional-python) ⭐ 2,552 | 🐛 8 | 📅 2026-06-23
* [Awesome F# - A curated list of awesome F# frameworks, libraries, software and resources](https://github.com/fsprojects/awesome-fsharp) ⭐ 1,429 | 🐛 6 | 🌐 F# | 📅 2026-03-21
* [Awesome PureScript - A curation of awesome PureScript libraries, resources and shiny things](https://github.com/passy/awesome-purescript) ⭐ 483 | 🐛 9 | 📅 2022-11-30
* [Awesome Haskell - A curated list of awesome Haskell frameworks, libraries and software](https://github.com/uhub/awesome-haskell) ⭐ 467 | 🐛 6 | 📅 2026-08-12
* [Awesome Coq - A curated list of awesome Coq frameworks, libraries and software](https://github.com/uhub/awesome-coq) ⭐ 234 | 🐛 2 | 📅 2026-08-06

***

## Books

* [Mostly adequate guide to FP (in javascript)](https://github.com/MostlyAdequate/mostly-adequate-guide) ⭐ 23,831 | 🐛 92 | 🌐 JavaScript | 📅 2024-09-17
* [A book about functional programming in JavaScript](https://github.com/getify/functional-light-js) ⭐ 16,739 | 🐛 27 | 🌐 JavaScript | 📅 2023-12-26
* [Functional Javascript Workshop (console based tutorial)](https://github.com/timoxley/functional-javascript-workshop) ⭐ 2,040 | 🐛 83 | 🌐 JavaScript | 📅 2020-10-08
* [Mostly adequate guide to FP (in javascript) - russian version](https://github.com/MostlyAdequate/mostly-adequate-guide-ru) ⭐ 1,228 | 🐛 6 | 🌐 JavaScript | 📅 2023-05-04
* [Functional Reactive Programming](https://www.manning.com/books/functional-reactive-programming)
* [Functional Programming in Java](https://www.manning.com/books/functional-programming-in-java)
* [Functional Programming in C++](https://www.manning.com/books/functional-programming-in-cplusplus)
* [Functional Programming in C#](https://www.manning.com/books/functional-programming-in-c-sharp)
* [Functional Programming in Kotlin](https://www.manning.com/books/functional-programming-in-kotlin)
* [Functional Concurrency in .NET](https://www.manning.com/books/functional-concurrency-in-dotnet)
* [Elm in Action](https://www.manning.com/books/elm-in-action?a_aid=elm_in_action\&a_bid=b15edc5c)
* [Functional JavaScript](https://jcouyang.gitbooks.io/functional-javascript/content/en/index.html)
* [Functional Programming in JavaScript - Dan Mantyla](https://www.amazon.com/Functional-Programming-JavaScript-Dan-Mantyla/dp/1784398225)
* [Functional JavaScript: Introducing Functional Programming with Underscore.js - Michael Fogus](https://www.amazon.com/Functional-JavaScript-Introducing-Programming-Underscore-js/dp/1449360726/)
* [A big list of books about functional programming](http://alexott.net/en/fp/books)
* [PureScript by Example](https://leanpub.com/purescript/read)
* [Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire](http://eprints.eemcs.utwente.nl/7281/01/db-utwente-40501F46.pdf)
* [Lenses in Functional Programming](https://www21.in.tum.de/teaching/fp/SS15/papers/17.pdf)
* [The Weird World of Bi-Directional Programming](https://www.cis.upenn.edu/~bcpierce/papers/lenses-etapsslides.pdf)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript)
* [Excerpt Funtional Programming JavaScript](http://cooperpress.s3.amazonaws.com/Excerpt_FPJavaScript.pdf)
* [Elm tutorial book](http://www.elm-tutorial.org/index.html)
* [Purescript Pux](http://www.alexmingoia.com/purescript-pux)
* [The Neophyte's Guide to Scala](http://danielwestheide.com/scala/neophytes.html)
* [Elm by Example - Grzegorz Balcerek](http://elm-by-example.org)
* [Learn you a Haskell for great good! (A beginner's guide)](http://learnyouahaskell.com/)
* [Learning Haskell](http://learn.hfm.io/)
* [Programming with Refinement Types - An Introduction to LiquidHaskell](http://ucsd-progsys.github.io/liquidhaskell-tutorial/)
* [learning Scalaz](http://eed3si9n.com/learning-scalaz/)
* [Learn you some Erlang for great good!](http://learnyousomeerlang.com/)
* [О Haskell по-человечески](https://www.ohaskell.guide/)
* [F# for Fun and Profit eBook](https://swlaschin.gitbooks.io/fsharpforfunandprofit/content/)
* [An Introduction to Elm](http://guide.elm-lang.org/)
* [Learn you an Agda](http://learnyouanagda.liamoc.net/toc.html)
* [Learn F#](https://www.manning.com/books/learn-fsharp)
* [The Transparent Web](https://manning.com/books/the-transparent-web)
* [JavaScript Allongé, the "Six" Edition](https://leanpub.com/javascriptallongesix/read)
* [Parallel Computing: Theory and Practice](http://www.cs.cmu.edu/afs/cs/academic/class/15210-f15/www/tapp.html)
* [Haskell Tutorial and Cookbook](https://leanpub.com/haskell-cookbook/read)
* [Розплутаний ClojureScript](https://lambdabooks.github.io/clojurescript-unraveled/)
* [Get Programming with Haskell](https://www.manning.com/books/get-programming-with-haskell)
* [Haskell in Depth](https://www.manning.com/books/haskell-in-depth)
* [Grokking Simplicity: Taming complex software with functional thinking - Eric Normand](https://www.manning.com/books/grokking-simplicity)
* [Functional Programming in Scala, Second Edition](https://www.manning.com/books/functional-programming-in-scala-second-edition)
* [Functional Programming in C#, Second Edition](https://www.manning.com/books/functional-programming-in-c-sharp-second-edition)
* [Grokking Functional Programming](https://www.manning.com/books/grokking-functional-programming)
* [Functional Programming in Kotlin](https://www.manning.com/books/functional-programming-in-kotlin)
* [Grokking Simplicity](https://www.manning.com/books/grokking-simplicity)
* [Functional Programming, Simplified](https://alvinalexander.com/scala/functional-programming-simplified-book/)
* [Clojure for the Brave and True](https://www.braveclojure.com/clojure-for-the-brave-and-true/)
* [OCaml Programming: Correct + Efficient + Beautiful](https://cs3110.github.io/textbook/cover.html)

***

## Resources

* [A book series on JavaScript](https://github.com/getify/You-Dont-Know-JS) ⭐ 184,702 | 🐛 2 | 📅 2026-02-15
* [functional-programming-jargon - Jargon from the functional programming world in simple terms](https://github.com/hemanth/functional-programming-jargon) ⭐ 18,645 | 🐛 27 | 📅 2023-10-17
* [Learn Haskell](https://github.com/bitemyapp/learnhaskell) ⭐ 8,032 | 🐛 13 | 🌐 Makefile | 📅 2026-07-20
* [A curated list of awesome functional programming stuff in js](https://github.com/stoeffel/awesome-fp-js) ⭐ 6,036 | 🐛 1 | 📅 2026-01-15
* [Code, exercises, answers, and hints to go along with the book "Functional Programming in Scala"](https://github.com/fpinscala/fpinscala) ⭐ 5,849 | 🐛 130 | 🌐 Scala | 📅 2024-12-11
* [Building a modern functional compiler from first principles](https://github.com/sdiehl/write-you-a-haskell) ⭐ 3,481 | 🐛 31 | 🌐 Haskell | 📅 2021-01-11
* [Awesome Haskell](https://github.com/krispo/awesome-haskell) ⭐ 3,284 | 🐛 17 | 🌐 Python | 📅 2026-08-03
* [Functional Programming concepts, examples and patterns illustrated in Haskell, Ocaml and Python](https://github.com/caiorss/Functional-Programming) ⭐ 2,693 | 🐛 9 | 🌐 Haskell | 📅 2019-08-06
* [A puzzle game written on purescript](https://github.com/sharkdp/cube-composer) ⭐ 2,045 | 🐛 10 | 🌐 PureScript | 📅 2022-12-08
* [functional-javascript-workshop - a functional javascript workshop. No libraries required (i.e. no underscore), just ES5](https://github.com/timoxley/functional-javascript-workshop) ⭐ 2,040 | 🐛 83 | 🌐 JavaScript | 📅 2020-10-08
* [functional-frontend-architecture - A functional frontend framework.](https://github.com/paldepind/functional-frontend-architecture) ⭐ 1,437 | 🐛 9 | 🌐 JavaScript | 📅 2019-07-02
* [Simple examples to help you understand ES6](https://github.com/sgaurav/understanding-es6) ⭐ 1,120 | 🐛 9 | 🌐 JavaScript | 📅 2016-12-15
* [An overview of Elm syntax and features](https://github.com/izdi/elm-cheat-sheet) ⭐ 947 | 🐛 2 | 🌐 Elm | 📅 2018-04-27
* [Visual programming meets Haskell](https://github.com/viskell/viskell) ⭐ 679 | 🐛 22 | 🌐 Java | 📅 2017-04-19
* [FP101x - Functional Programming MOOC 2015 Content Repository](https://github.com/fptudelft/FP101x-Content-2015) ⭐ 515 | 🐛 0 | 🌐 Haskell | 📅 2015-12-20
* [Code Samples Functional Programming in JavaScript, Manning 2016](https://github.com/luijar/functional-programming-js) ⭐ 483 | 🐛 5 | 🌐 JavaScript | 📅 2018-12-09
* [A list of functional javascript resources](https://github.com/jkup/functional-javascript) ⭐ 395 | 🐛 1 | 📅 2022-09-02
* [Source code for blog post Journey from procedural to reactive JavaScript with stops](https://github.com/bahmutov/javascript-journey) ⭐ 332 | 🐛 4 | 🌐 JavaScript | 📅 2016-08-04
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript) ⭐ 302 | 🐛 2 | 📅 2020-10-01
* [js-funcional - A Cookbook for writing FP in JavaScript using ES6](https://github.com/js-functional/js-funcional) ⭐ 253 | 🐛 2 | 🌐 JavaScript | 📅 2023-09-07
* [Community driven Elm guide for JS people](https://github.com/elm-guides/elm-for-js) ⭐ 227 | 🐛 3 | 📅 2019-08-30
* [Total functional programming (ESFP)](https://github.com/mietek/total-functional-programming) ⭐ 189 | 🐛 0 | 📅 2019-02-15
* [Dependent Object Types (DOT)](https://github.com/namin/dot) ⭐ 162 | 🐛 0 | 📅 2016-09-08
* [djinn - Generate Haskell code from a type](https://github.com/augustss/djinn) ⭐ 150 | 🐛 3 | 🌐 Haskell | 📅 2025-02-21
* [The official supporting materials repository for LambdaConf 2015](https://github.com/degoes-consulting/lambdaconf-2015) ⭐ 90 | 🐛 1 | 🌐 JavaScript | 📅 2015-05-29
* [Formalization of the Dependent Object Types (DOT) calculus](https://github.com/samuelgruetter/dot-calculus) ⭐ 67 | 🐛 0 | 🌐 Coq | 📅 2022-08-30
* [Collection of examples on places where Elm is different to Haskell](https://github.com/eeue56/haskell-to-elm) ⭐ 66 | 🐛 0 | 📅 2017-02-05
* [Archive the best resources surrounding the functional programming paradigm for Javascript developers](https://github.com/radiovisual/functional-programming-resources) ⭐ 59 | 🐛 0 | 📅 2017-11-22
* [Kickstart your web development with Elm](https://github.com/eeue56/elm-for-web-developers) ⭐ 55 | 🐛 0 | 📅 2016-01-25
* [cor - The Language of the Web](https://github.com/yosbelms/cor) ⭐ 53 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-15
* [Pragmatic functional programming in JavaScript - Workshop material](https://github.com/staltz/fp-js-workshop) ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2016-05-24
* [λ List of resources related to Functional Programming in JS](https://github.com/codekult/adventures-of-lambda-in-JS) ⭐ 15 | 🐛 0 | 📅 2018-02-27
* [Haskell monads for learning purposes in javascript](https://github.com/raimohanska/Monads) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-11
* [JS-monads-stable](https://github.com/dschalk/JS-monads-stable) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-07
* [Answers to the exercises from https://github.com/MostlyAdequate/mostly-adequate-guide](https://github.com/gypsydave5/mostly-adequate-functional-answers) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2015-11-14
* [Explorations in Functional Land](https://github.com/svenschmidt75/Functional) ⭐ 0 | 🐛 0 | 🌐 Haskell | 📅 2017-07-25
* [ML Dialects and Haskell: SML, OCaml, F#, Haskell](http://hyperpolyglot.org/ml)
* [Haskell for OCaml programmers](http://science.raphael.poss.name/haskell-for-ocaml-programmers.html)
* [Free monads](https://gist.github.com/safareli/b43f43d3e65483b71b08b894386f4d71)
* [Functional Programming by Example](http://caiorss.github.io/Functional-Programming/) (\*\*\*)
* [Haskell by Example](https://lotz84.github.io/haskellbyexample/)
* [http://chris-taylor.github.io](http://chris-taylor.github.io/)
* [FPCasts - Your source for Functional Programing Related Podcasts](https://www.fpcasts.com/)
* [Blog Jakub Arnold](http://blog.jakubarnold.cz/)
* [Primers](https://jeremykun.com/primers/)
* [Railway Oriented Programming](http://fsharpforfunandprofit.com/rop/)
* [Материалы курсов по Clojure, бесплатно и онлайн](http://clojurecourse.by/)
* [24 Days of PureScript](https://gist.github.com/paf31/8e9177b20ee920480fbc)
* [Category Theory for Programmers: The Preface](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/)
* [The Glasgow Haskell Compiler. Simon Marlow and Simon Peyton-Jones](http://aosabook.org/en/ghc.html)
* [diagrams is a powerful, flexible, declarative domain-specific language for creating vector graphics, using the Haskell programming language.](http://projects.haskell.org/diagrams/)
* [24 Days of GHC Extensions](https://ocharles.org.uk/blog/pages/2014-12-01-24-days-of-ghc-extensions.html)
* <https://rosettacode.org/wiki/Category:Haskell>
* [Corecursion](https://en.wikipedia.org/wiki/Corecursion)
* [Pointfree.io - convert Haskell code into pointfree Haskell code](http://pointfree.io/)
* [Typeclassopedia](https://wiki.haskell.org/Typeclassopedia)
* [Philip Wadler's home page](http://homepages.inf.ed.ac.uk/wadler/)
* [Javascript Monad Transformers](http://akh-js.com/)
* [Functor](https://en.wikipedia.org/wiki/Functor)
* [http://fprog.ru](http://fprog.ru/)
* [Scala Tour](http://www.scala-tour.com/#/welcome)
* [An es6 js maybe monad, using generators](https://gist.github.com/torgeir/7618372)
* [Trying to apply ES6 generators to create monad comprehensions. Unfortunately it looks like this will not work with monads that contain multiple values, such as arrays](https://gist.github.com/hallettj/9827604)
* [Free monad based thread simulation and FRP constructs written in JavaScript](https://gist.github.com/jkpl/9ef31e82dea59be2be7f)
* [Luna. Visual and textual functional programming language with a focus on productivity, collaboration and development ergonomics](http://www.luna-lang.org/)
* [Conal Elliott blog](http://conal.net/blog)
* [Brian Lonsdorf on medium](https://medium.com/@drboolean)
* [Elm weekly](http://www.elmweekly.nl)
* [Almost all about monads](https://flipboard.com/topic/monad)
* [Notes, Thoughts, & Examples derived from reading Functional Javascript by Michael Fogus](https://github.com/hackerrdave/functional-javascript)
* [Functorial Blog - A blog about functional programming](http://blog.functorial.com/index.html)
* <http://functionaljavascript.blogspot.com>
* <http://buzzdecafe.github.io>
* <http://blog.codeprototype.com>
* <http://simplectic.com/blog>
* <http://joneshf.github.io>
* <http://www.luisatencio.net>
* <http://bartoszmilewski.com>
* <http://rebcabin.github.io>
* [http://blog.jakubarnold.cz](http://blog.jakubarnold.cz/)
* [https://juxt.pro/radar.html - The 2016 JUXT Clojure Technology Radar](https://juxt.pro/radar.html)
* [http://clojurewerkz.org - A growing collection of open source Clojure libraries](http://clojurewerkz.org)
* [http://www.parsonsmatt.org - Elm, Haskell, Purescript](http://www.parsonsmatt.org)
* [Lo-Fi Learning - Advanced topics from our blackboard to your screen](http://school.looprecur.com)
* [FunctionalTalks.org - Brilliant people giving brilliant talks on Functional Programming.](http://functionaltalks.org)
* [gist of functional utils which written on ES6](https://gist.github.com/bendc/9b05735dfa6966859025)
* [Introduction to Functional Programming (course from edx.org)](https://www.edx.org/course/introduction-functional-programming-delftx-fp101x-0)
* [Category theory jargon cheat sheet](https://gist.github.com/cb372/b1bad150e0c412fb7364)
* [Functional Programming in Javascript (Online tutorial)](http://reactivex.io/learnrx)
* [Contravariance is the Dual of Covariance](http://www.infoq.com/presentations/covariance-contravariance-joy-of-coding-2014)
* [Functional programming (page on wiki of Haskell)](https://wiki.haskell.org/Functional_programming)
* [Category Theory Presentation](http://yannesposito.com/Scratch/en/blog/Category-Theory-Presentation)
* [A Guide to Functional Programming Lingo for JavaScripters](https://gist.github.com/ericelliott/ea925c58410f0ae74aef)
* [Cheat sheet for Monads in Haskell](https://dkalemis.wordpress.com/2014/08/02/cheat-sheet-for-monads-in-haskell)
* [Monad](https://wiki.haskell.org/Monad)
* [Monad (in computer science)](http://ncatlab.org/nlab/show/monad+\(in+computer+science\))
* [The Indexed Continuation Monad in Haskell, Scala, and C#](https://gist.github.com/pthariensflame/5716594)
* [Informatics 1: Functional Programming](https://www.inf.ed.ac.uk/teaching/courses/inf1/fp)
* [Functional Programming in Javascript (online exercises)](http://reactivex.io/learnrx)
* [Category Theory for Programmers: The Preface](http://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface)
* [Ramtuary REPL](http://davidchase.github.io/ramtuary)
* [Haskell for Maths](http://haskellformaths.blogspot.com)
* [Y combinator](http://rosettacode.org/wiki/Y_combinator)
* [A collection about Functional Reactive Programming in Swift](https://github.com/onmyway133/functional-swift)
* [Patterns in Functional Programming](https://patternsinfp.wordpress.com)
* [What I Wish I Knew When Learning Haskell](http://dev.stephendiehl.com/hask)
* [Введение в функциональное программирование на скале](http://www.otstavnov.com/Odersky_Scala_lecture-notes.html)
* [Monoidal Contravariant Functors and Transducers](https://gist.github.com/DrBoolean/fdef9e08352ac42754f1)
* [Unofficial a documentation of lodash-fp](https://gist.github.com/jfmengels/6b973b69c491375117dc#_castarrayvalue)
* [Coeffects: Context-aware programming languages](http://tomasp.net/coeffects/)
* [Neon - Experimental PureScript standard library](https://gist.github.com/tfausak/96411fd7400aa06478675c7e6c75ebd4)
* [forwardcourses about functional programming](https://forwardcourses.com/lectures/track/fp)
* [Monad tutorials timeline](https://wiki.haskell.org/Monad_tutorials_timeline)
* [JSON to Elm](http://eeue56.github.io/json-to-elm/)
* [functionalcs.github.io](https://functionalcs.github.io/curriculum)
* [Haskell MOOC](https://haskell.mooc.fi/)
* [A Functional Introduction To Computer Science (Part I)](https://cs.uwaterloo.ca/~plragde/flaneries/FICS/)
* [A Functional Introduction To Computer Science (Part II)](https://cs.uwaterloo.ca/~plragde/flaneries/FICS2/)

***

### Combinators

* [To Dissect a Mockingbird: A Graphical Notation for the Lambda Calculus with Animated Reduction](http://dkeenan.com/Lambda/index.htm)
* [Combinator Birds](http://www.angelfire.com/tx4/cus/combinator/birds.html)
* [Deriving the Y Combinator in 7 Easy Steps](http://igstan.ro/posts/2010-12-01-deriving-the-y-combinator-in-7-easy-steps.html)
* [B, C, K, W system](https://en.wikipedia.org/wiki/B,_C,_K,_W_system)
* [Комбинаторы — это просто!](https://ru.wikibooks.org/wiki/%D0%9A%D0%BE%D0%BC%D0%B1%D0%B8%D0%BD%D0%B0%D1%82%D0%BE%D1%80%D1%8B_%E2%80%94_%D1%8D%D1%82%D0%BE_%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%BE!)
* [Комбинаторная логика как формальная система](http://www.ict.edu.ru/ft/005135/ch5.pdf)
* [combinators-js](https://www.npmjs.com/package/combinators-js)
* [SKI combinator calculus](https://en.wikipedia.org/wiki/SKI_combinator_calculus)
* [Combinators](https://gist.github.com/Avaq/1f0636ec5c8d6aed2e45)
* [Fixed-point combinator](https://en.wikipedia.org/wiki/Fixed-point_combinator)
* [Combinatory logic](https://en.wikipedia.org/wiki/Combinatory_logic)
* [Collected Lambda Calculus Functions](http://jwodder.freeshell.org/lambda.html)
* [Combinatory Logic](http://plato.stanford.edu/entries/logic-combinatory/) (\*)
* [Combinatory Logic: Finding and Evaluating Combinators](https://www.npmjs.com/package/combilog)
* [Maths - Combinatory Logic](http://www.euclideanspace.com/maths/discrete/logic/combinatory/index.htm)
* [Lambda Calculus](http://softoption.us/content/node/30)
* [From Lambda calculus to Combinator Calculus](http://goodmath.blogspot.com/2006/05/from-lambda-calculus-to-combinator.html)
* [The SKI Combinator Calculus a universal formal system](http://people.cs.uchicago.edu/~odonnell/Teacher/Lectures/Formal_Organization_of_Knowledge/Examples/combinator_calculus/)
* [Lambda Calculus](http://dev.stephendiehl.com/fun/lambda_calculus.html)
* [Combinatory logic](https://esolangs.org/wiki/Combinatory_logic)
* [The Y Combinator (no, not that one). A crash-course on lambda calculus](https://medium.com/@ayanonagon/the-y-combinator-no-not-that-one-7268d8d9c46#.eigwi23hd)
* [The Quantum Electrodynamics of Functional JavaScript](http://raganwald.com/2015/02/13/functional-quantum-electrodynamics.html)
* [Applicative Functor / SKI combinator calculus](https://gist.github.com/tinybyte/3302086)

***

## Presentations

* [Awesomely descriptive JavaScript with monads](https://docs.google.com/presentation/d/12GpX3AXTS6uJHqRK_Q3RgkIg9ZTr4r37N0MTkk0CL14/edit#slide=id.p)
* [Functional Programming from Brian Lonsdorf (awesome presentation)](https://docs.google.com/presentation/d/1YOJ2hU60KcXJ3m3CG28EtfTO4t1OP_JR0gpM82i2xcI/edit#slide=id.g338d117be_040)
* [Functional Programming Patterns](http://www.slideshare.net/ScottWlaschin/fp-patterns-buildstufflt) (must have)
* [Domain Modeling in a Functional World](http://www.slideshare.net/debasishg/qconny-12)
* [Functional Programming in JavaScript](http://www.slideshare.net/LuisAtencio3/functional-programming-in-javascript-by-luis-atencio)
* [ECMAScript 6 Quiz](http://maxwellito.github.io/es6-quiz-slides)
* [Functional Programming from Scott Sauyet](http://scott.sauyet.com/Javascript/Talk/FunctionalProgramming)
* [FKit: Everyday Functional Programming in JavaScript](https://speakerdeck.com/nullobject/fkit-everyday-functional-programming-in-javascript)
* [Ramda: Practical Functional Javascript](http://slides.com/andydrew/ramda-js-curry-compose)
* [Category theory, Monads, and Duality in the world of (BIG) Data](http://www.slideshare.net/greenwop/category-theory-monads-and-duality-in-the-world-of-big-data)
* [Functional Programming in 5 Minutes](http://slides.com/gsklee/functional-programming-in-5-minutes)
* [Introduction to Functional Programming](http://slides.com/jingchuanchen/intro-to-fp)
* [Monads](http://slides.com/aripaasonen/monads)
* [Pragmatic Functional Programming](http://slides.com/rossmurray/pragmatic-functional-programming)
* [Intro to Functional Programming](http://www.slideshare.net/firthh/intro-to-functional-programming-levelup-brisbane)
* [Who's More Functional: Kotlin, Groovy, Scala, or Java?](http://www.slideshare.net/abreslav/whos-more-functional-kotlin-groovy-scala-or-java)
* [Introduction to Functional Programming in JavaScript](http://www.slideshare.net/tmont/introduction-to-functional-programming-in-javascript)
* [Category Theory: An Abstraction for Anything](http://www.infoq.com/presentations/category-theory)
* [Немного о функциональном программирование в JavaScript](http://pt.slideshare.net/fwdays/javascript-47497140)
* [Category theory for beginners](http://www.slideshare.net/kenbot/category-theory-for-beginners)
* [Getting Started with PureScript by Michael Ficarra](https://speakerdeck.com/michaelficarra/getting-started-with-purescript)
* [Functional Programming Forever](http://slides.com/thomasomans/functional-programming-forever#/)
* [Why Haskell?](http://slides.com/etrepum/preview-intro-to-haskell)
* [PureScript](https://docs.google.com/presentation/d/1IOM9A3Otxufs5xzvYb3yPrT7JDVPhkJVkdaWvVl8R_E/pub?start=false\&loop=false\&delayms=3000\&slide=id.ge5fcfef40_0_5)
* [Анонимные записи в Haskell](http://www.slideshare.net/cblpsu/3-anonymous-records)
* [Better know a language PureScript](http://taylor.fausak.me/static/pages/2015-10-22-better-know-a-language-purescript.html)
* [Functional Patterns in JavaScript](http://slides.com/hackbulgaria/functional-patterns-in-javascript#/)
* [Collections libraries in JavaScript](http://slides.com/sashqa/deck#/)
* [Transducers - Reducing complexity with reducers](http://slides.com/plaid/deck#/)
* [Remove the Boilerplate](http://slides.com/bahmutov/remove-the-boilerplate#/)
* [Functional Programming. Patterns in Scala](http://jsuereth.com/intro-to-fp/preso.html)
* [Map, Flatmap and Reduce are Your New Best Friends: Simpler Collections, Concurrency, and Big Data](http://www.slideshare.net/chris.e.richardson/map-flatmap-and-reduce-are-your-new-best-friends-simpler-collections-concurrency-and-big-data-oscon)
* [Functional Programming in JavaScript by Luis Atencio](http://www.slideshare.net/LuisAtencio3/functional-programming-in-javascript-by-luis-atencio)
* [CodeMash: Functional Programming Basics in ES6](https://speakerdeck.com/jfairbank/codemash-functional-programming-basics-in-es6)
* [Fluent Conf: Rise of Async JavaScript ](https://speakerdeck.com/jfairbank/fluent-conf-rise-of-async-javascript)
* [Монады для барабанщиков](http://www.slideshare.net/cblpsu/ss-60053562)
* [Building Functional Islands by Mark Jones](https://speakerdeck.com/thisismarkup/building-functional-islands)
* [Reactive UIs with Halogen](https://docs.google.com/presentation/d/1uwKxJzNx8pBL2QCUKYy2mgkEbrCdEjKbYOj3mJ4nyEo/edit#slide=id.g775150948_0_41)
* [Fun\* JavaScript Workshop - Dr. Gleb Bahmutov PhD](http://slides.com/bahmutov/fun-javascript-workshop#/)
* [TYPESAFE SQL IN HASKELL - AN INTRODUCTION TO OPALEYE](http://opaleye.benkolera.com/#/)
* [Playing with Graphics and Animations in Haskell by Manuel Chakravarty](https://speakerdeck.com/mchakravarty/playing-with-graphics-and-animations-in-haskell)
* [Practically workshop](https://www.slideshare.net/secret/3IPPDiGR2QXNEz)

***

## Videos

* [Jason Ganetsky on Making a Fast Curry: Push/Enter vs. Eval/Apply for Higher-order Languages](http://paperswelove.org/2015/video/jason-ganetsky-fast-curry)
* [Erik Meijer: Functional Programming](https://www.youtube.com/watch?v=z0N1aZ6SnBk)
* [Lambda Days 2015 - Kuba Waliński - Fun with Functional JavaScript](https://www.youtube.com/watch?v=WY3q6Np7PwM)
* [Functional Programming with Kotlin](https://www.youtube.com/watch?v=AhA-Q7MOre0\&list=WL\&index=63)
* [Category theory for JavaScript programmers](https://www.youtube.com/playlist?list=PLwuUlC2HlHGe7vmItFmrdBLn6p0AS8ALX)
* ["Everything Old is New Again: Quoted Domain Specific Languages" by Philip Wadler](https://www.youtube.com/watch?v=DlBwJ4rvz5c)
* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY\&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC)
* [FP-Syd - PureScript: An Overview for Haskellers by Tim Docker (Jul 2015)](https://www.youtube.com/watch?v=udg01o2M4iY)
* [Intro to PureScript -- Utah Haskell Meetup](https://www.youtube.com/watch?v=9a57V3bvzaI)
* [Haskell Programming Tutorial](https://www.youtube.com/watch?v=Sinr-kVzsLI\&list=PLa8a_8vztYc4Y5HPptfBhLNZxNgCkWEOr)
* [Monad a day 1: Reader](https://vimeo.com/105300347)
* [Monad a day 2: Future](https://vimeo.com/106008027)
* [Monad a day 3: State](https://vimeo.com/109984691)
* [Lenses Quick n’ Dirty](https://vimeo.com/104807358)
* [Frontend Masters Workshop finish up](https://vimeo.com/97575933)
* [Professor Frisby Introduces Composable Functional JavaScript](https://egghead.io/courses/professor-frisby-introduces-function-composition)
* [A Million Ways to Fold in JS](https://www.youtube.com/watch?v=JZSoPZUoR58)
* [Coyoneda in Javascript](https://www.youtube.com/watch?v=WH5BrkzGgQY)
* [Freer Monad (We define Maybe and IO in the freer monad)](https://www.youtube.com/watch?v=RkDtMeZXMTA)
* [Free(er) Monads in JS pt 2 (Defining an interpreter for multiple natural transformations)](https://www.youtube.com/watch?v=KFCEJUjsdQg)
* [What is pure functional programming, and how it can improve our application testing? by Luca Molteni](https://www.youtube.com/watch?v=dOJPDH4461k)
* [Start Using Elm to Build Web Applications](https://egghead.io/courses/start-using-elm-to-build-web-applications)
* [How to Create Tetris in Elm](https://www.youtube.com/watch?v=GMSXYnMH1gg\&list=PL7C8fMD-89DKhlerIE3BrYNd0PlhA6Zch)
* [Scott Wlaschin - Railway Oriented Programming — error handling in functional languages](https://vimeo.com/97344498)
* [Lambda Jam 2014 - Eric Meijer - The Lost Art of Denotational Semantics](https://www.youtube.com/watch?v=pOl4E8x3fmw)
* [SKI School: The Combinator Calculus Demystified](https://www.youtube.com/watch?v=FC6kl_kLFEo)
* [Erik Meijer - Functional Programming From First Principles](https://www.youtube.com/watch?v=mhKl7Ppp_ao)
* [Russian videos about clojure and clojurescript](https://www.youtube.com/watch?v=jguG9rwa6oo\&list=PLHOTezm7WWkmk_NxC51xwnC2YsAut_5vX)
* [Parallel and Concurrent Haskell](https://www.youtube.com/watch?v=N6sOMGYsvFA\&list=PLbgaMIhjbmEm_51-HWv9BQUXcmHYtl4sw)
* [Functional programming patterns for the non-mathematician (cut)](https://www.youtube.com/watch?v=AvgwKjTPMmM)
* [Brian Beckman: Don't fear the Monad](https://www.youtube.com/watch?v=ZhuHCtR3xq8)
* [Brian Beckman: The Zen of Stateless State - The State Monad](https://www.youtube.com/watch?v=XxzzJiXHOJs)
* [Monads and Gonads](https://www.youtube.com/watch?v=b0EF0VTs9Dc)
* [Haskell Tutorial](https://www.youtube.com/watch?v=02_H3LjqMr8)
* [YOW! Lambda Jam 2016 Conor McBride - What are Types for, or are they only Against?](https://www.youtube.com/watch?v=3U3lV5VPmOU)
* [Phil Freeman - Fun with Profunctors](https://www.youtube.com/watch?v=OJtGECfksds)
* [Monads, Monoids and Composition w/ Functional JavaScript](https://www.youtube.com/watch?v=ZQSU4geXAxM)
* [«PureScript livecoding» by Dmirti Bushenko](https://www.youtube.com/watch?v=Sc3ci8j7Wok\&list=PLtAOYbbqpTmxg5fTJK7e8ZXdGzYLROsRm\&index=11)
* [Learning Functional Programming with JavaScript by Anjana Vakil at JSUnconf 2016](https://www.youtube.com/watch?v=e-5obm1G_FY)
* [Elm in Purescript](https://www.youtube.com/watch?v=O_kWwaghZ9U)
* [Pure Functional Database Programming with Fixpoint Types—Rob Norris](https://www.youtube.com/watch?v=7xSfLPD6tiQ)
* [Functional JS - Lenses - JavaScript](https://www.livecoding.tv/evilsoft/videos/d5BDO-functional-js-lenses)
* ["Point-Free or Die: Tacit Programming in Haskell and Beyond" by Amar Shah](https://www.youtube.com/watch?v=seVSlKazsNk)
* [The fuel for the Functional Programming engine](https://youtu.be/3G9wOODP7y4) - Michal Plachta
* [Functional Programming with TypeScript](https://www.youtube.com/playlist?list=PLuPevXgCPUIMbCxBEnc1dNwboH6e2ImQo)

***

## Youtube channels

* [Functional Works](https://www.youtube.com/channel/UCE6NivlVPGUn3TMtDAeL2vQ)
* [Scala World](https://www.youtube.com/channel/UCc0j7uOItUDh7vEvPb-TeCg)
* [ruHaskell](https://www.youtube.com/channel/UCbIkFj1mYQI7lmrc5BXGyAg)
* [Brian Lonsdorf](https://www.youtube.com/channel/UCKjVLbSDoM-8-eEM7A30igA)
* [jasonofthel33t](https://www.youtube.com/user/jasonofthel33t)
* [Лекториум](https://www.youtube.com/user/OpenLektorium)
* [Scala Russia](https://www.youtube.com/channel/UCR4iuvbk9DCuieR1ADIi0-Q)
* [Manning Publications](https://www.youtube.com/channel/UCDia_lkNYKLJVLRLQl_-pFw)
* [Web Village Voyage](https://www.youtube.com/@webvv)

***

## Libraries

### [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

***

* [**async** - Async utilities for node and the browser](https://github.com/caolan/async) ⭐ 28,139 | 🐛 23 | 🌐 JavaScript | 📅 2026-08-07
* [**fantasy-land** - Specification for interoperability of common algebraic structures in JavaScript](https://github.com/fantasyland/fantasy-land) ⭐ 10,240 | 🐛 36 | 🌐 JavaScript | 📅 2024-11-10
* [**este** - Dev stack and starter kit for functional and universal React web apps](https://github.com/este/este) ⚠️ Archived
* [**Sugar** - A Javascript library for working with native objects](https://github.com/andrewplummer/Sugar) ⭐ 4,504 | 🐛 95 | 🌐 JavaScript | 📅 2024-06-13
* [**sanctuary** - Refuge from unsafe JavaScript](https://github.com/plaid/sanctuary) ⭐ 3,052 | 🐛 36 | 🌐 JavaScript | 📅 2024-11-10 [official site](http://sanctuary.js.org)
* [**Fluture** - A complete Fantasy Land compatible Future library](https://github.com/Avaq/Fluture) ⭐ 2,493 | 🐛 12 | 🌐 JavaScript | 📅 2024-04-22
* [**js-csp** - Communicating sequential processes for Javascript (like Clojurescript core.async, or Go)](https://github.com/ubolonton/js-csp) ⭐ 2,321 | 🐛 36 | 🌐 JavaScript | 📅 2022-07-20
* [**asyncawait** - Callback heaven for Node.js with async/await](https://github.com/yortus/asyncawait) ⭐ 1,897 | 🐛 8 | 🌐 TypeScript | 📅 2022-04-28
* [**linq** - linq.js - LINQ for JavaScript library](https://github.com/mihaifm/linq) ⭐ 1,732 | 🐛 19 | 🌐 JavaScript | 📅 2024-05-19
* [**transducers.js** - A small library for generalized transformation of data (inspired by Clojure's transducers)](https://github.com/jlongster/transducers.js) ⭐ 1,719 | 🐛 21 | 🌐 JavaScript | 📅 2017-06-12
* [**purify** - Functional programming library for TypeScript focusing on ADTs](https://github.com/gigobyte/purify) ⭐ 1,603 | 🐛 2 | 🌐 TypeScript | 📅 2025-12-16
* [**transducers-js** - A high performance Transducers implementation for JavaScript](https://github.com/cognitect-labs/transducers-js) ⚠️ Archived
* [**Crocks - A collection of well known Monadic Containers for your utter enjoyment.**](https://github.com/evilsoft/crocks) ⭐ 1,598 | 🐛 69 | 🌐 JavaScript | 📅 2023-01-06
* [**ramda-fantasy** - Fantasy-Land compatible types for easy integration with Ramda.js](https://github.com/ramda/ramda-fantasy) ⭐ 1,499 | 🐛 21 | 🌐 JavaScript | 📅 2022-01-31
* [**trine** - A utility library for modern JavaScript](https://github.com/jussi-kalliokoski/trine) ⭐ 1,411 | 🐛 24 | 🌐 JavaScript | 📅 2020-01-09
* [**partial.lenses** - Partial lenses is a comprehensive, high-performance optics library for JavaScript](https://github.com/calmm-js/partial.lenses) ⭐ 922 | 🐛 23 | 🌐 JavaScript | 📅 2021-11-18
* [**linq.ts** - LinQ for TypeScript](https://github.com/kutyel/linq.ts) ⭐ 880 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-15
* [**streamjs** - Lazy Object Streaming Pipeline for JavaScript](https://github.com/winterbe/streamjs) ⭐ 858 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-19
* [**1-liners** - Functional tools that couldn’t be simpler](https://github.com/1-liners/1-liners) ⭐ 799 | 🐛 28 | 🌐 JavaScript | 📅 2023-04-16
* [**contra** - Asynchronous flow control with a functional taste to it](https://github.com/bevacqua/contra) ⭐ 776 | 🐛 1 | 🌐 JavaScript | 📅 2024-03-16
* [**static-land** - Specification for common algebraic types in JavaScript based on Fantasy Land](https://github.com/rpominov/static-land) ⭐ 776 | 🐛 11 | 🌐 JavaScript | 📅 2019-10-29
* [**daggy** - Library for creating tagged constructors](https://github.com/puffnfresh/daggy) ⭐ 708 | 🐛 2 | 🌐 JavaScript | 📅 2021-07-19
* [**neo-async** - Neo-Async is thought to be used as a drop-in replacement for Async, it almost fully covers its functionality and runs faster](https://github.com/suguru03/neo-async) ⭐ 654 | 🐛 15 | 🌐 JavaScript | 📅 2022-12-02
* [**fkit** - A functional programming toolkit for JavaScript](https://github.com/nullobject/fkit) ⭐ 582 | 🐛 2 | 🌐 JavaScript | 📅 2021-08-31
* [**lodash-fp** - lodash with auto-curried iteratee-first data-last methods](https://github.com/lodash/lodash-fp) ⚠️ Archived
* [**kneden** - Transpile ES7 async/await to vanilla ES6 Promise chains: a Babel plugin](https://github.com/marten-de-vries/kneden) ⚠️ Archived
* [**async-to-gen** - Transform async functions to generator functions with speed and simplicity](https://github.com/leebyron/async-to-gen) ⭐ 507 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-15
* [**immutable-ext** - fantasyland extensions for immutablejs](https://github.com/DrBoolean/immutable-ext) ⭐ 489 | 🐛 5 | 🌐 JavaScript | 📅 2019-02-10
* [**union-type** - A small JavaScript library for defining and using union types](https://github.com/paldepind/union-type) ⭐ 479 | 🐛 18 | 🌐 JavaScript | 📅 2019-06-05
* [**pointfree-fantasy** - Point free wrappers for fantasy land](https://github.com/DrBoolean/pointfree-fantasy) ⭐ 450 | 🐛 5 | 🌐 JavaScript | 📅 2017-10-08
* [**flow-static-land** - Implementation of common algebraic types in JavaScript + Flow](https://github.com/gcanti/flow-static-land) ⚠️ Archived
* [**TsMonad** - Little monad library designed for TypeScript](https://github.com/cbowdon/TsMonad) ⚠️ Archived
* [**nimble** - A really tiny functional JavaScript and async flow-control library](https://github.com/caolan/nimble) ⭐ 327 | 🐛 3 | 🌐 JavaScript | 📅 2011-11-14
* [**async-csp** - CSP style channels using ES7 async/await](https://github.com/dvlsg/async-csp) ⭐ 317 | 🐛 6 | 🌐 JavaScript | 📅 2017-11-08
* [**scour** - Traverse objects and arrays with ease](https://github.com/rstacruz/scour) ⭐ 304 | 🐛 10 | 🌐 JavaScript | 📅 2020-07-17
* [**nodent** - Asynchronous Javascript language extensions](https://github.com/MatAtBread/nodent) ⭐ 287 | 🐛 3 | 🌐 JavaScript | 📅 2020-09-02
* [**f** - Implementing native versions of Haskell functions according to JavaScript ES6 standards](https://github.com/casualjs/f) ⭐ 286 | 🐛 2 | 🌐 JavaScript | 📅 2016-08-20
* [**creed** - Sophisticated and functionally-minded async with advanced features: coroutines, promises, ES2015 iterables, fantasy-land](https://github.com/briancavalier/creed) ⭐ 277 | 🐛 16 | 🌐 JavaScript | 📅 2018-05-29
* [**sanctuary-type-classes** - Standard library for Fantasy Land](https://github.com/sanctuary-js/sanctuary-type-classes) ⭐ 239 | 🐛 3 | 🌐 JavaScript | 📅 2024-11-10
* [**kewler** - Simple functional and immutable color manipulation library](https://github.com/adriantoine/kewler) ⭐ 230 | 🐛 3 | 🌐 JavaScript | 📅 2017-07-01
* [**adt.js** - Algebraic data types for Javascript](https://github.com/natefaubion/adt.js) ⚠️ Archived
* [**lenses** - Composable kmett style lenses](https://github.com/DrBoolean/lenses) ⭐ 216 | 🐛 3 | 🌐 JavaScript | 📅 2015-09-28
* [**ramda-lens** - Lens library built on ramda](https://github.com/ramda/ramda-lens) ⭐ 184 | 🐛 4 | 🌐 JavaScript | 📅 2017-06-13
* [**maryamyriameliamurphies.js** - A library of Haskell-style morphisms ported to ES2015 JavaScript using Babel](https://github.com/sjsyrek/maryamyriameliamurphies.js) ⭐ 182 | 🐛 19 | 🌐 JavaScript | 📅 2017-05-27
* [**burrido** - Do-notation for JavaScript](https://github.com/pelotom/burrido) ⭐ 179 | 🐛 1 | 🌐 JavaScript | 📅 2017-04-19
* [**freeky** - Free monad Collection](https://github.com/DrBoolean/freeky) ⭐ 176 | 🐛 7 | 🌐 JavaScript | 📅 2018-04-13
* [**futurize** - Turn callback-style functions or promises into futures](https://github.com/futurize/futurize) ⭐ 145 | 🐛 29 | 🌐 JavaScript | 📅 2017-05-24
* [**csp** - CSP/Actor/Transducer Experiments](https://github.com/phuu/csp) ⚠️ Archived
* [**immutagen** - A library for simulating immutable generators in JavaScript](https://github.com/pelotom/immutagen) ⭐ 126 | 🐛 1 | 🌐 JavaScript | 📅 2019-07-19
* [**fantasy-lenses** - Composable, immutable getters and setters](https://github.com/fantasyland/fantasy-lenses) ⚠️ Archived
* [**barely-functional** - tiny (2.7kb) functional programming library using native es5/6 operations](https://github.com/cullophid/barely-functional) ⭐ 105 | 🐛 0 | 🌐 JavaScript | 📅 2017-10-26
* [**imlazy** - Functional, declarative, immutable and lazy as you like](https://github.com/benji6/imlazy) ⭐ 104 | 🐛 7 | 🌐 JavaScript | 📅 2026-04-02
* [**fantasy-birds** - port of the haskell package Data.Aviary.Birds. Every thing for your combinatory needs](https://github.com/fantasyland/fantasy-birds) ⚠️ Archived
* [**transduce** - JavaScript transducers](https://github.com/transduce/transduce) ⭐ 92 | 🐛 8 | 🌐 JavaScript | 📅 2016-11-20
* [**jabz** - Powerful and practical abstractions for JavaScript and TypeScript. Functors, Monads, Traversables and all that jazz](https://github.com/paldepind/jabz) ⭐ 89 | 🐛 6 | 🌐 TypeScript | 📅 2018-06-06
* [**underarm** - Transducers Inspired by Underscore](https://github.com/kevinbeaty/underarm) ⭐ 87 | 🐛 0 | 🌐 JavaScript | 📅 2016-02-02
* [**optics** - This library is an implementation of profunctor optics using JS, heavily influenced by the PureScript Profunctor Lenses and Kmett's Lens libraries.](https://github.com/flunc/optics) ⭐ 87 | 🐛 1 | 🌐 JavaScript | 📅 2016-05-05
* [**culljs** - Functional javascript for adults - no cushions included](https://github.com/culljs/culljs) ⭐ 74 | 🐛 2 | 🌐 JavaScript | 📅 2017-01-03
* [**udon** - Practical functional programming in JavaScript](https://github.com/beastaugh/udon) ⭐ 71 | 🐛 0 | 🌐 JavaScript | 📅 2012-08-29
* [**fantasydo** - Do-notation for javascript fantasy land](https://github.com/russellmcc/fantasydo) ⭐ 64 | 🐛 0 | 🌐 JavaScript | 📅 2014-01-18
* [**it.js** - Chainable object-oriented functional combinators](https://github.com/dtinth/it.js) ⭐ 60 | 🐛 0 | 🌐 JavaScript | 📅 2013-11-06
* [**Idealist** - Functional HTTP micro-framework](https://github.com/Avaq/Idealist) ⭐ 59 | 🐛 2 | 🌐 JavaScript | 📅 2021-04-06
* [**free** - Combination of a free applicative functor and free monad](https://github.com/safareli/free) ⭐ 58 | 🐛 8 | 🌐 JavaScript | 📅 2020-08-09
* [**medium** - CSP-style channel library using ES7 async/await keywords](https://github.com/bbarr/medium) ⭐ 55 | 🐛 2 | 🌐 JavaScript | 📅 2024-06-16
* [**chained-promise** - Functional programming tools for recurring promises](https://github.com/google/chained-promise) ⚠️ Archived
* [**switch-fn** - Write a functional switch statement](https://github.com/ajoslin/switch-fn) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-25
* [**redash** - Compact library for writing performant functional JavaScript](https://github.com/davezuko/redash) ⚠️ Archived
* [**conjs** - a featured fork of mori, with core.async included](https://github.com/jcouyang/conjs) ⭐ 29 | 🐛 0 | 🌐 Clojure | 📅 2016-03-23
* [**asyncp** - Port of the async library to use Promises](https://github.com/jgornick/asyncp) ⭐ 28 | 🐛 2 | 🌐 JavaScript | 📅 2016-10-13
* [**asyncbox** - A collection of ES7 async/await utilities](https://github.com/jlipps/asyncbox) ⭐ 27 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-30
* [**monadic** - Do-notation and Monads for JavaScript](https://github.com/five-eleven/monadic) ⚠️ Archived
* [**monad-transformers** - Practical monad transformers for JS](https://github.com/boris-marinov/monad-transformers) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-27
* [**pure-random** - A purely functional random number generator](https://github.com/Risto-Stevcev/pure-random) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2016-03-06
* [**fantasy-frees** - Free monads](https://github.com/fantasyland/fantasy-frees) ⚠️ Archived
* [**alicates** - Small library for functional programming with ES2015+](https://github.com/gonzaloruizdevilla/alicates) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2015-10-22
* [**List-in-JS** - List in JS provides List like List of Haskell. List in JS implements Fantasy Land Specification. List is a Setoid, a Semigroup, a Monoid, a Functor, an Applicative Functor, Foldable, Traversable, a Chain and a Monad](https://github.com/PandaNoir/List-in-JS/) ⭐ 21 | 🐛 1 | 🌐 JavaScript | 📅 2017-08-28
* [**prelude** - Base functional programming utils for mostjs packages](https://github.com/mostjs/prelude) ⭐ 20 | 🐛 1 | 📅 2017-06-16
* [**nux** - A Push-Based Functional Reactive UI Library for the Web](https://github.com/marknutter/nux) ⭐ 19 | 🐛 8 | 🌐 JavaScript | 📅 2024-01-05
* [**gentoo** - Tools for ES6 generators](https://github.com/sashee/gentoo) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2016-05-18
* [**fantasy-states** - State control structure](https://github.com/fantasyland/fantasy-states) ⚠️ Archived
* [**lazy-either** - A lazy implementation of the Fantasy Land Either type](https://github.com/Risto-Stevcev/lazy-either) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-22
* [**cat.js** - Category Theory for JavaScript](https://github.com/jcouyang/cat.js) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2016-07-20
* [**future-io** - A fantasy-land compliant monadic IO library for Node.js.](https://github.com/futurize/future-io) ⭐ 14 | 🐛 11 | 🌐 JavaScript | 📅 2017-05-30
* [**mandolin** - Painlessly enhance your JavaScript with monadic types](https://github.com/bioball/mandolin) ⭐ 14 | 🐛 7 | 🌐 JavaScript | 📅 2015-10-22
* [**do-notation** - Do notation for Fantasy Land monad types](https://github.com/Risto-Stevcev/do-notation) ⭐ 13 | 🐛 1 | 🌐 JavaScript | 📅 2016-04-18
* [**monady** - Composable monads for functional async flow](https://github.com/GeorgeSapkin/monady) ⚠️ Archived
* [**doM.js** - "do" monad syntax for JavaScript](https://github.com/elclanrs/doM.js) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2013-12-22
* [**co-functional** - co-functional is a MIT licenced library that provides several functions for use with the co library](https://github.com/N0ps32/co-functional) ⭐ 10 | 🐛 2 | 🌐 JavaScript | 📅 2016-01-25
* [**fantasy-do** - Do notation for javascript](https://github.com/jwoudenberg/fantasy-do) ⚠️ Archived
* [**async-ls** - Higher order functions, compositions and common operations for asynchronous programming in LiveScript](https://github.com/homam/async-ls) ⭐ 9 | 🐛 1 | 🌐 LiveScript | 📅 2014-08-17
* [**iterablejs** - Lazy-loading wrapper for iterable items and common functional programming operations](https://github.com/dvlsg/iterablejs) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2016-05-19
* [**parallel-future** - Run Futures in parallel](https://github.com/futurize/parallel-future) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2016-03-05
* [**fantasy-derivations** - Use methods on ADTs whether or not they're defined](https://github.com/rjmk/fantasy-derivations) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2016-04-25
* [**operajonal** - Implementation of free monads in JavaScript, based on Haskell's operational package](https://github.com/phipsgabler/operajonal) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2019-10-12
* [**funkit** - Functional toolkit for javascript](https://github.com/mwardle/funkit) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-24
* [**akh-cont** - Akh continuation monad and monad transformer](https://github.com/mattbierner/akh-cont) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-03
* [**funko** - Naive minimalistic functional programming library](https://github.com/mickvangelderen/funko) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-27
* [**ez-dom** - Functional library to manipulate the DOM](https://github.com/jonathandion/ez-dom) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-06
* [**Slack** - Lazy functional JS library](https://github.com/loosechainsaw/Slack) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2016-01-11
* [**fops** - Curried, functional operators](https://github.com/nickb1080/fops) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2015-12-02
* [**florida** - Pure functional accessor factories in js](https://github.com/Hypercubed/florida) ⚠️ Archived
* [**tiny-tuple** - Tiny Tuple library for Client or Server](https://github.com/avoidwork/tiny-tuple) ⚠️ Archived
* [**Lodash** - A JavaScript utility library delivering consistency, modularity, performance, & extras](https://lodash.com)
* [**Ramda** - A practical functional library for Javascript programmers](http://ramdajs.com)
* [**functional.js** - The functional JavaScript library](http://functionaljs.com)
* [**wu.js** - is a JavaScript library providing higher order functions (such as map, filter, and reduce) for ECMAScript 6 iterators](http://fitzgen.github.io/wu.js)
* [**folktalejs** - Robust, Scalable, DRY. Folktale is a suite of libraries for generic functional programming in JavaScript that allows you to write elegant modular applications with fewer bugs, and more reuse](http://folktalejs.org)
* [**fn.js** - A JavaScript library built to encourage a functional programming style & strategy](http://eliperelman.com/fn.js)
* [**bilby.js** - is a serious functional programming library](http://bilby.brianmckenna.org)
* [**lazy.js** - is a functional utility library for JavaScript, similar to Underscore and Lo-Dash, but with an underlying engine that supports many more use cases than those libraries, while offering comparable or superior performance in most scenarios](http://danieltao.com/lazy.js)
* [**monet.js** - Monadic types library for JavaScript](http://cwmyers.github.com/monet.js)
* [**lamb** - A lightweight, and docile, JavaScript (ES5) library to help embracing functional programming](http://ascartabelli.github.io/lamb)
* [**ftoer** - A pragmatic library facilitating functional programming in javascript](https://github.com/ftoer/ftoer)
* [**chunkify** - A functional API to unblock your JavaScript](https://github.com/yangmillstheory/chunkify)
* [**cali** - A JavaScript utility library with a functional programming flavor](https://github.com/jedirandy/cali)
* [**QIO** - Purely functional effect management library for Typescript.](https://qio.netlify.com)

### [Livescript](https://github.com/gkz/LiveScript) ⭐ 2,371 | 🐛 174 | 🌐 LiveScript | 📅 2024-03-05

***

* [**prelude.ls** - is a functionally oriented utility library](http://www.preludels.com)
* [**monolith-ls** - Experimental fork of `prelude-ls`, gives a more functional feel to prelude.](https://github.com/masterrace/monolith-ls)

### [Java](http://www.oracle.com/technetwork/java/index.html)

***

* [**Frege** - is a Haskell for the JVM. It brings purely functional programing to the Java platform.](https://github.com/Frege/frege) ⭐ 3,709 | 🐛 44 | 🌐 Frege | 📅 2026-07-11
* [**functionaljava** - Functional programming in Java](https://github.com/functionaljava/functionaljava) ⭐ 1,620 | 🐛 32 | 🌐 Java | 📅 2023-04-25
* [**Jinq** - LINQ-style queries for Java 8](https://github.com/my2iu/Jinq) ⭐ 661 | 🐛 36 | 🌐 Java | 📅 2025-06-08
* [**linq4j** - A port of LINQ (Language-Integrated Query) to Java](https://github.com/julianhyde/linq4j) ⭐ 378 | 🐛 3 | 🌐 Java | 📅 2023-12-17
* [**yeti** - Functional programming language for JVM](https://github.com/mth/yeti) ⭐ 255 | 🐛 12 | 🌐 Java | 📅 2025-12-18
* [**javaz** - Java 8 lambda experiment](https://github.com/mariofusco/javaz) ⭐ 15 | 🐛 0 | 🌐 Java | 📅 2014-06-29
* [**TotallyLazy** - A complete functional environment for Java](http://totallylazy.com)
* [**Vavr** - (formerly called Javaslang) object-functional library that runs with Java 8+](https://www.vavr.io/)

### [Clojure](https://github.com/clojure/clojure) ⭐ 10,950 | 🐛 0 | 🌐 Java | 📅 2026-07-29/[ClojureScript](https://github.com/clojure/clojurescript) ⭐ 9,388 | 🐛 7 | 🌐 Clojure | 📅 2026-08-10

***

* [**jank** - A statically typed functional programming language](https://github.com/jeaye/jank) ⭐ 3,314 | 🐛 84 | 🌐 C++ | 📅 2026-08-17
* [**lux** - The Lux Programming Language](https://github.com/LuxLang/lux) ⭐ 1,739 | 🐛 0 | 🌐 Emacs Lisp | 📅 2026-08-05
* [**cats** - Category Theory and Algebraic abstractions for Clojure and ClojureScript](https://github.com/funcool/cats) ⭐ 969 | 🐛 33 | 🌐 Clojure | 📅 2025-03-20

### [ClojureScript](https://github.com/clojure/clojurescript) ⭐ 9,388 | 🐛 7 | 🌐 Clojure | 📅 2026-08-10

***

* [**re-frame** - A Reagent Framework For Writing SPAs, in Clojurescript](https://github.com/Day8/re-frame) ⭐ 5,541 | 🐛 23 | 🌐 Clojure | 📅 2026-05-05

### [Scala](https://github.com/scala/scala) ⭐ 14,566 | 🐛 14 | 🌐 Scala | 📅 2026-08-18

***

* [**scalaz** - An extension to the core Scala library for functional programming](https://github.com/scalaz/scalaz) ⭐ 4,673 | 🐛 154 | 🌐 Scala | 📅 2026-08-17
* [**macroid** - A modular functional UI language for Android](https://github.com/macroid/macroid) ⚠️ Archived
* [**Structures** - Functional type classes for Scala](https://github.com/mpilquist/Structures) ⚠️ Archived
* [**rillit** - Boilerplate-free Functional Lenses for Scala 2.10](https://github.com/akisaarinen/rillit) ⭐ 90 | 🐛 2 | 🌐 Scala | 📅 2014-08-12
* [**cats** - Lightweight, modular, and extensible library for functional programming](https://github.com/non/cats) ⭐ 29 | 🐛 0 | 🌐 Scala | 📅 2017-09-03

### [Kotlin](https://github.com/JetBrains/kotlin) ⭐ 53,334 | 🐛 403 | 🌐 Kotlin | 📅 2026-08-18

***

* [**funKTionale** - Functional constructs for Kotlin](https://github.com/MarioAriasC/funKTionale) ⭐ 914 | 🐛 11 | 🌐 Kotlin | 📅 2019-12-19
* [**Forge** - Functional style JSON parsing written in Kotlin](https://github.com/kittinunf/Forge) ⭐ 130 | 🐛 1 | 🌐 Kotlin | 📅 2022-01-14
* [**funktional** - Kotlin monads](https://github.com/mplatvoet/funktional) ⭐ 10 | 🐛 0 | 🌐 Kotlin | 📅 2016-04-29
* [**Arrow** - Functional programming library, which adds patterns, type classes and more](http://arrow-kt.io/)
* [**kotlinslang** - A functional library for Kotlin that provides functional control structures. Inspired by javaslang](https://github.com/kotlinslang/kotlinslang)

### [F#](https://github.com/fsharp/fsharp) ⚠️ Archived

***

* [**FSharpPlus** - A complete and extensible base library for F#.](https://github.com/gusty/FSharpPlus) ⭐ 939 | 🐛 66 | 🌐 F# | 📅 2026-08-12
* [**FSharpx.Extras** - Functional programming and other utilities](https://github.com/fsprojects/FSharpx.Extras) ⭐ 697 | 🐛 10 | 🌐 F# | 📅 2025-12-20
* [**Streams** - A lightweight F#/C# library for efficient functional-style pipelines on streams of data](https://github.com/nessos/Streams) ⭐ 384 | 🐛 12 | 🌐 F# | 📅 2020-05-22
* [**freya** - Functional-first web stack, including an HTTP finite state machine, built on top of OWIN](https://github.com/freya-fs/freya) ⚠️ Archived
* [**chiron** - Functional JSON library for F#](https://github.com/xyncro/chiron) ⭐ 173 | 🐛 28 | 🌐 F# | 📅 2018-10-10
* [**Juniper** - FRP (Functional Reactive Programming) for the Arduino and other microcontrollers](https://github.com/calebh/Juniper) ⭐ 99 | 🐛 8 | 🌐 F# | 📅 2024-11-16
* [**hekate** - Purely Functional Graphs for F#](https://github.com/xyncro/hekate) ⭐ 57 | 🐛 0 | 🌐 F# | 📅 2018-10-09
* [**Fable** - F# to JavaScript Compiler](https://github.com/fsprojects/Fable) ⚠️ Archived
* [**Lw** - is a general-purpose statically-typed functional language with advanced features.](https://github.com/alvisespano/Lw) ⭐ 8 | 🐛 0 | 🌐 F# | 📅 2022-07-25
* [**micron** - A minimalistic pure functional programming language](https://github.com/jonathanvdc/micron) ⭐ 2 | 🐛 0 | 🌐 F# | 📅 2016-05-19
* [**ReactFSharp** - Proof of concept demo implementing a React like declarative UI API for F# on top of RX](https://github.com/bordoley/ReactFSharp) ⭐ 0 | 🐛 0 | 🌐 F# | 📅 2016-08-02

### [C#](https://github.com/dotnet/roslyn) ⭐ 20,611 | 🐛 6,298 | 🌐 C# | 📅 2026-08-18

***

* [**language-ext** - C# functional language extensions and 'Erlang like' concurrency system](https://github.com/louthy/language-ext) ⭐ 7,082 | 🐛 15 | 🌐 C# | 📅 2026-07-29
* [**FuncSharp** - Functional programming in C#](https://github.com/siroky/FuncSharp) ⭐ 104 | 🐛 22 | 🌐 C# | 📅 2025-11-20
* [**csharp-probability-monad** - A probabilistic programming framework for C#](https://github.com/joashc/csharp-probability-monad) ⭐ 97 | 🐛 2 | 🌐 C# | 📅 2019-10-27
* [**Ramda.NET** - Practical functional C# port from Ramda.js](https://github.com/sagifogel/Ramda.NET) ⭐ 22 | 🐛 0 | 🌐 C# | 📅 2018-04-04
* [**monadsharp** - A collection of monads for C# that provide some functional programming flavor](https://github.com/kallanreed/monadsharp) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2016-05-21
* [**functional.net** - Library of functions and list extensions for C#](https://github.com/jallen720/functional.net)

### [Swift](https://developer.apple.com/swift)

***

* [**Argo** - Functional JSON parsing library for Swift](https://github.com/thoughtbot/Argo) ⭐ 3,471 | 🐛 10 | 🌐 Swift | 📅 2021-09-24
* [**Swiftz** - Functional programming in Swift](https://github.com/typelift/Swiftz) ⭐ 3,319 | 🐛 12 | 🌐 Swift | 📅 2022-06-30
* [**Interstellar** - Simple and lightweight Functional Reactive Coding in Swift for the rest of us](https://github.com/JensRavens/Interstellar) ⚠️ Archived
* [**Prelude** - Swift µframework of simple functional programming tools](https://github.com/robrix/Prelude) ⭐ 410 | 🐛 3 | 🌐 Swift | 📅 2018-07-19
* [**SwiftSequence** - A μframework of extensions for SequenceType in Swift 2.0, inspired by Python's itertools, Haskell's standard library, and other things](https://github.com/oisdk/SwiftSequence) ⭐ 374 | 🐛 1 | 🌐 Swift | 📅 2016-10-22
* [**SINQ** - LINQ for Swift - Swift Integrated Query](https://github.com/slazyk/SINQ) ⭐ 268 | 🐛 2 | 🌐 Swift | 📅 2019-05-03
* [**Swiftx** - Functional data types and functions for any project](https://github.com/typelift/Swiftx) ⭐ 221 | 🐛 4 | 🌐 Swift | 📅 2019-11-21
* [**Concurrent** - Functional Concurrency Primitives](https://github.com/typelift/Concurrent) ⭐ 208 | 🐛 5 | 🌐 Swift | 📅 2019-10-05
* [**Funky** - Functional programming tools and experiments in Swift](https://github.com/brynbellomy/Funky) ⭐ 13 | 🐛 0 | 🌐 Swift | 📅 2016-01-16
* [**LlamaKit** - Collection of must-have functional Swift tools](https://github.com/LlamaKit/LlamaKit) ⭐ 0 | 🐛 0 | 📅 2025-02-19
* [**Swift for Windows** - is a free, open source tool that provide runtime environment for swift programming language to compile and run on Windows OS with graphical interface](https://swiftforwindows.codeplex.com/)
* [**Dollar.swift** - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript](http://www.dollarswift.org)
* [**Functional** - A functional programming framework for Swift](https://github.com/broomburgo/Functional)

### [Python](https://www.python.org/)

***

* [**toolz** - A functional standard library for Python](https://github.com/pytoolz/toolz) ⭐ 5,151 | 🐛 135 | 🌐 Python | 📅 2026-01-01
* [**funcy** - A fancy and practical functional tools](https://github.com/Suor/funcy) ⭐ 3,509 | 🐛 15 | 🌐 Python | 📅 2026-08-17
* [**fn.py** - Functional programming in Python: implementation of missing features to enjoy FP](https://github.com/kachayev/fn.py) ⭐ 3,368 | 🐛 33 | 🌐 Python | 📅 2022-08-30
* [**f** - Functional stuff for Python](https://github.com/igrishaev/f) ⭐ 120 | 🐛 1 | 🌐 Python | 📅 2016-07-30
* [**pyMonet** - High abstract library for functional programming. Contains algebraic data structures known from Haskell or Scala](https://github.com/przemyslawjanpietrzak/pyMonet) ⭐ 36 | 🐛 4 | 🌐 Python | 📅 2026-04-13
* [**Coconut** - Simple, elegant, Pythonic functional programming](http://coconut-lang.org/)

### [PHP](https://github.com/php/php-src) ⭐ 40,290 | 🐛 1,993 | 🌐 C | 📅 2026-08-17

***

* [**functional-php** - Primitives for functional programming in PHP](https://github.com/lstrojny/functional-php) ⭐ 1,984 | 🐛 16 | 🌐 PHP | 📅 2026-03-21
* [**Pinq** - PHP Integrated Query, a real LINQ library for PHP](https://github.com/TimeToogo/Pinq) ⚠️ Archived
* [**YaLinqo** - Yet Another LINQ to Objects for PHP](https://github.com/Athari/YaLinqo) ⭐ 453 | 🐛 13 | 🌐 PHP | 📅 2025-10-19
* [**Non-standard PHP library (NSPL)** - Compact functional programming oriented code and more](https://github.com/ihor/Nspl) ⭐ 374 | 🐛 6 | 🌐 PHP | 📅 2022-05-30
* [**pramda** - Practical Functional Programming in PHP](https://github.com/kapolos/pramda) ⭐ 244 | 🐛 6 | 🌐 PHP | 📅 2018-06-10
* [**ginq** - LINQ to Object inspired DSL for PHP](https://github.com/akanehara/ginq) ⭐ 192 | 🐛 6 | 🌐 PHP | 📅 2022-06-30
* [**prelude** - Functional library for PHP](https://github.com/sergiors/prelude) ⭐ 48 | 🐛 1 | 🌐 PHP | 📅 2018-03-16

### [Rust](https://github.com/rust-lang/rust) ⭐ 115,564 | 🐛 12,704 | 🌐 Rust | 📅 2026-08-18

***

* [**elmesque** - An attempt at porting Elm's incredibly useful, purely functional std graphics modules](https://github.com/mitchmindtree/elmesque) ⭐ 146 | 🐛 10 | 🌐 Rust | 📅 2015-12-22

### [Julia](https://github.com/JuliaLang/julia) ⭐ 49,009 | 🐛 4,613 | 🌐 Julia | 📅 2026-08-18

***

* [**Lazy.jl** - Functional programming for Julia](https://github.com/one-more-minute/Lazy.jl) ⭐ 485 | 🐛 45 | 🌐 Julia | 📅 2021-06-01
* [**FunctionalCollections.jl** - Functional and persistent data structures for Julia](https://github.com/JuliaLang/FunctionalCollections.jl) ⭐ 126 | 🐛 18 | 🌐 Julia | 📅 2025-11-24

### [Go](https://github.com/golang/go) ⭐ 135,874 | 🐛 10,232 | 🌐 Go | 📅 2026-08-17

***

* [**go-linq** - .NET LINQ-like query methods for Go](https://github.com/ahmetalpbalkan/go-linq) ⭐ 3,661 | 🐛 3 | 🌐 Go | 📅 2026-08-17
* [**The Oden Programming Language** - Oden is an experimental, statically typed, functional programming language, built for the Go ecosystem](https://oden-lang.org/)

### [Haskell](https://www.haskell.org)

***

* [**futhark** - A data-parallel functional programming language](https://github.com/HIPERFIT/futhark) ⭐ 2,793 | 🐛 79 | 🌐 Haskell | 📅 2026-08-14
* [**ghcvm** - A Haskell to JVM compiler that supports GHC Haskell](https://github.com/rahulmutt/ghcvm) ⭐ 2,633 | 🐛 242 | 🌐 Haskell | 📅 2022-07-31
* [**reflex** - Practical Functional Reactive Programming](https://github.com/reflex-frp/reflex) ⭐ 1,115 | 🐛 87 | 🌐 Haskell | 📅 2026-08-14
* [**ivorylang** - is an eDSL for safe systems programming. You can think of Ivory as a safer C, embedded in Haskell](http://ivorylang.org/index.html)

### [Elixir](https://github.com/elixir-lang/elixir) ⭐ 26,598 | 🐛 29 | 🌐 Elixir | 📅 2026-08-16

***

### [Erlang](https://www.erlang.org)

***

* [**lfe** - Lisp Flavoured Erlang (LFE)](https://github.com/rvirding/lfe) ⭐ 2,451 | 🐛 28 | 🌐 Erlang | 📅 2026-08-05

### [OCaml](https://ocaml.org/)

***

* [**bucklescript** - A backend for the OCaml compiler which emits JavaScript](https://github.com/bloomberg/bucklescript) ⭐ 7,431 | 🐛 171 | 🌐 ReScript | 📅 2026-08-18

### [Racket](https://racket-lang.org/)

***

* [**hackett** - (Very) WIP implementation of a Haskell 98-like Lisp in Racket](https://github.com/lexi-lambda/hackett) ⭐ 1,205 | 🐛 36 | 🌐 Racket | 📅 2024-04-14

## Languages

* [Koka](https://github.com/koka-lang/koka) ⭐ 4,028 | 🐛 290 | 🌐 Koka | 📅 2026-08-15 - A function-oriented language with effect inference
* [Agda](https://github.com/agda/agda) ⭐ 2,916 | 🐛 1,047 | 🌐 Haskell | 📅 2026-08-14 - A dependently typed functional programming language
* [Ditto](https://github.com/ditto/ditto) ⭐ 178 | 🐛 0 | 🌐 Haskell | 📅 2018-07-12 - A super kawaii dependently typed language for you!
* [Lean](https://leanprover.github.io/) - Lean is a functional programming language that makes it easy to write correct and maintainable code.
* [Pyret](http://www.pyret.org/) - A programming language designed to serve as an outstanding choice for programming education while exploring the confluence of scripting and functional programming
* [Ela](http://elalang.net/) - A dynamic functional language
* [Eta](http://eta-lang.org/) - A powerful language for building scalable systems on the JVM
* [F\*](https://www.fstar-lang.org/) - (pronounced F star) An ML-like functional programming language aimed at program verification
* [Idris](http://www.idris-lang.org/) - A general purpose pure functional programming language with dependent types
* [Coq](https://coq.inria.fr/) - A formal proof management system. It provides a formal language to write mathematical definitions, executable algorithms and theorems together with an environment for semi-interactive development of machine-checked proofs

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
