# My Web Development Study Guide

### **A Poem of HTTP**
A client sends a request to a shop across the street,.  
**DNS** finds the house, the number is discreet,.  
Data travels in **packets**, small chunks for the ride,.  
**HTTP** is the language, with the server as the guide,.

***

### **How Files are "Parsed" in the Browser**
When you load a website, the browser acts like a factory that takes raw materials—the **HTML, CSS, and JavaScript** code—and outputs a finished product, which is the web page you see. The browser **interprets and assembles** these different programming languages to display the content correctly. This process involves reading the files and following their instructions to build the page's structure, look, and behavior,.

***

### **Finding Images for a Website**
You can find images using **Google Images**, but it is important to remember that most images on the web are protected by copyright. To find images you can legally use, click the **"Tools"** button, select **"Usage rights,"** and choose **"Creative Commons licenses"**. Once you find an image, you can right-click and "Save Image As…" to your computer.

***

### **Creating Strings vs. Numbers in JavaScript**
In JavaScript, **Strings** are pieces of text used for labels or messages, such as "Player 1: Chris". They are often created by wrapping text in quotation marks or backticks. **Numbers** are numeric values that the computer can use for mathematical operations, such as adding values together,.

***

### **What is a Variable and Why is it Important?**
A **variable** is a container that stores a value. They are fundamental in JavaScript because they allow you to **store useful data** (like a user's name) and **reference that data** later in your code without having to re-enter it,. For example, you can capture a name once and then use it to display a personalized message throughout the site,.

***

### **Introduction to HTML**

#### **What is an HTML Attribute?**
Attributes provide **extra information** about an HTML element that does not appear in the actual content of the page. They contain settings or information, such as `src` (to tell an image where its file is) or `alt` (to provide a text description for visually impaired users).

#### **Anatomy of an HTML Element**
An HTML element typically consists of three parts:
1.  **Opening Tag:** The name of the element (like `p` for paragraph) wrapped in angle brackets (`<p>`).
2.  **Content:** The actual text or data being displayed.
3.  **Closing Tag:** The same as the opening tag but with a forward slash before the name (`</p>`) to show where the element ends.

#### **Difference Between `<article>` and `<section>`**
*   **`<article>`** is used to enclose a block of related content that makes sense on its own, like a single blog post or news story.
*   **`<section>`** is used to group together a specific part of a page that shares a single theme or piece of functionality, like a map or a set of summaries.

#### **Elements of a Typical Website**
A "typical" website structure usually includes:
*   **Header:** A strip at the top with a heading and logo.
*   **Navigation Bar:** Links to the main sections of the site.
*   **Main Content:** The unique information for that specific page.
*   **Sidebar:** Extra info like ads, quotes, or related links.
*   **Footer:** A strip at the bottom for fine print, copyright, or contact info.

#### **Metadata and Search Engine Optimization (SEO)**
Metadata is "data about data". Providing descriptions and keywords in your metadata can help your website appear **higher in search engine results**. Search engines use this information to determine how relevant your page is to what a user is searching for.

#### **How the `<meta>` Tag is Used**
The `<meta>` tag is used in the `<head>` of a document to provide information that cannot be represented by other tags. It is commonly used to:
*   Specify **character encoding** (like `utf-8`) so the browser can display all human languages correctly.
*   Define the **author** or a **description** of the page using `name` and `content` attributes.

***

### **Miscellaneous: Designing a Website**

#### **The First Step to Designing a Website**
The first step is **defining what you want to accomplish**. This phase, known as **project ideation**, is necessary to give your project direction before you start worrying about the technical side or code.

#### **The Most Important Question**
The most important question you must answer is: **"What exactly do I want to accomplish?"**. Listing and prioritizing your goals helps you decide what features to build and which tools to use,.

***

### **Semantics**

#### **Why Use `<h1>` Over `<span>`?**
You should use `<h1>` because it is a **semantic element**, meaning it tells the browser that the text is a **top-level heading**. While a `<span>` can be styled to *look* like a heading, it has no semantic value; the computer won't recognize its importance, which is the "right tool for the job".

#### **Benefits of Using Semantic Tags**
*   **SEO:** Search engines see these tags as important keywords.
*   **Accessibility:** Screen readers use them as signposts to help visually impaired users navigate,.
*   **Maintainability:** It is much easier for developers to understand and find meaningful blocks of code.

***

### **What is JavaScript?**

#### **2 Things That Require JavaScript in the Browser**
1.  **Dynamic Content Updates:** JavaScript allows a page to update its interface, like generating a new table of data, without reloading the whole page.
2.  **Complex Interactivity:** Features like interactive maps, animated graphics, and scrolling video jukeboxes rely on JavaScript to function,.

#### **How to Add JavaScript to an HTML Document**
JavaScript is added using the **`<script>`** element. You can do this in two ways:
*   **Internal:** Placing the code directly between `<script>` and `</script>` tags, usually at the bottom of the HTML body.
*   **External:** Placing the code in a separate `.js` file and linking it in the HTML using the `src` attribute (e.g., `<script src="script.js"></script>`). Using `type="module"` in the head is the recommended modern way to ensure the HTML loads before the script runs,.

## Things I want to know more about-