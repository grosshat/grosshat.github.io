JavaScript is fundamentally about objects. Arrays are
objects. Functions are objetcts. Objects are objects.

So, What the hell are Objects?
==============================

Objects are collections of name-value pairs.

	Names -> strings
	Values -> strings, numbers, booleans, objects (arrays,
	functions)

Objects are usually implemented as hashtables. So values can be
retrieved quickly.

If a value is a function, we consider it a method. When a method of an
object is invoked, the _this_ variable is set to the object.

Objects can be produced by constructors, which are functions which
initialize objects.

Closures
========

An inner function always has access to the vars and parameters of its
outer function, even after the outer function has returned.

function init() {
    var name = "local variable created by init";
    function displayName() {
	console.log(name);
    }
    displayName();
}
init();

And same result for this other code.

function makeFunc() {
    var name = "local variable created by init";
    function displayName() {
	console.log(name)
    }
    return displayName;
}

var myFunc = makeFunc();
myFunc();

A closure is a special kind of object that combines two things: a
function, and the environment in which that function was created. The
environment consists of any local variables that were in-scope at the
time that the closure was created.

}
