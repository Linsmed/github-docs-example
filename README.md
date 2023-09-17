# github-docs-example

- When you can , you should attempt to apply syntax highlighting to your codeblocks
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
num = 5
result = factorial(num)
puts "The factorial of #{num} is #{result}"

```
<img width='200px' src='https://github.com/Linsmed/github-docs-example/assets/99271201/437de84b-cabd-4e2f-a501-82a9bcbe6bb0'/>

Good Cloud Engineers use codeblocks for for both codes and errors that appear in the console.

```bash
Traceback (most recent call last):
  example.rb:1:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)
```
> Here is an example of error that appears in the bash.

## Step 3 - Use Github Flavored  Markdown Task Lists
- [x] finish step 1
- [x] finish step 2
-  [x] finish step 3
Github extends  markdown to have a list where you can check off items.<sup>[1]</sup>

## References
- [Github flavored markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[1]</sup>
- https://github.com/Linsmed/github-docs-example/edit/main/README.md


