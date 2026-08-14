# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**

Accessibility means designing websites so that people with different abilities can use and navigate them effectively. Labels make form inputs more accessible by clearly identifying what information a user should enter and by allowing screen readers to associate the label with the correct input. They also provide a larger clickable area when properly connected to an input with the for attribute and matching id.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**

The for attribute on a <label> connects the label to a specific <input> by matching the input’s id, which improves accessibility and allows users to click the label to focus the input. The id uniquely identifies an element in the HTML and is used by the label’s for attribute and JavaScript to select that element. The name attribute identifies the form field when the form data is submitted and is used as the key for the input’s value.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**

Specific input types like type="email" and type="number" provide built-in validation and help the browser understand what kind of data the user should enter. They can also improve the user experience by providing appropriate keyboards on mobile devices and useful controls, such as number inputs with increment/decrement buttons. Using specific types makes forms more accessible and helps prevent invalid data from being submitted.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**

A real-world example is Instagram’s login form, where a user enters their username or email and password. The form data is sent to Instagram’s server, which checks the credentials against the user’s account information and, if they are correct, authenticates the user and allows them to access their account.
