# Programming Styles

This is the starter template for the labs 
of the **Programming Styles** course at USI.

Note that all labs where you need to implement
the *term frequency* task use this exact same starter template.

## Testing your program

You can test that your program produces the correct output
by running our simple testing infrastructure.

First, install the dependencies with:

```
npm install
```

Then, you can run the `test.js` script with Node.js.
You need to specify the input `size`, the target programming `lang`uage and the file/class name.

As an example, this command uses a small input for a JavaScript implementation written in `TermFrequency.js`.

```
node test --size small --lang javascript --main TermFrequency
```

The script will run your program (after compiling it `javac`, in case of Java)
and check its output.

To see all the options and their descriptions, run `node test --help`.
