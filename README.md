<h1>Anonymous Methods</h1>

We discussed that delegates are used to reference any methods that
has the same signature as that of the delegate.

In other words, you can call a method that can be referenced by a
delegate using that delegate object.

Anonymous methods provide a technique to pass a code block as a
delegate parameter.

Anonymous methods are the methods without a name, just the body.

Writing an Anonymous Method

Anonymous methods are declared with the creation of the delegate
instance, with a delegate keyword.

delegate void NumberChanger(int n);

NumberChanger nc = delegate(int x) {

Console.WriteLine("Anonymous Method: {0}", x);

};

The code block Console.WriteLine("Anonymous Method: {0}", x); is
the body of the anonymous method.

The delegate could be called both with anonymous methods as well
as named methods in the same way, i.e., by passing the method
parameters to the delegate object.
