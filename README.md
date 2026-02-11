# Demoblaze-Ecommerce-selenium-tutorial

This repository contains Selenium automation for the Demoblaze e-commerce website.  
Currently, the automation is implemented in **Python**. The JavaScript version will be added in a future update.

## Test Scenario Automated
<ol>
  <li>Visit https://www.demoblaze.com/index.html#</li>
  <li>Register yourself as a user (you can use random data).</li>
  <li>Add Sony vaio i5 to cart.</li>
  <li>Add ASUS Full HD to cart.</li>
  <li>Go to cart.</li>
  <li>Check if cart has 2 products.</li>
  <li>Purchase the products in the cart.</li>
  <li>Go to cart and verify that it is empty.</li>
  <li>Make a purchase with the empty cart.</li>
  <li>Create a <code>contact.txt</code> file.</li>
  <li>Fill the contact form with the following data:
  <br><img width="584" height="123" alt="image" src="https://github.com/user-attachments/assets/c6b57782-84f5-48cd-9677-b162434ee188" />
</li>
  <li>
    For each contact request, write the form details in <code>contact.txt</code> file in the following format:
    <pre>
New Contact Request:
Today’s date: &lt;date&gt;
Current time: &lt;time&gt;
Email: &lt;email&gt;
Name: &lt;name&gt;
Message: &lt;message&gt;
---
    </pre>
  </li>
  <li>Go to laptops section.</li>
  <li>Go to 2nd page.</li>
  <li>Add MacBook Pro to the cart.</li>
  <li>Add Dell i7 8gb to the cart.</li>
  <li>Get product description of Dell i7 8gb.</li>
  <li>Go to cart.</li>
  <li>Get total amount.</li>
  <li>Remove Dell i7 8gb from the cart.</li>
  <li>Purchase the items from the cart.</li>
</ol>


## How to Run the Automation (Python)

Note that The automation code is available in the **`python` branch**.

<ol>
  <li>
    Switch to the <code>python</code> branch:
    <pre><code>git switch python</code></pre>
  </li>

  <li>
    Ensure the following files are present in the same directory:
    <ul>
      <li><code>main.py</code></li>
      <li><code>driver_setup.py</code></li>
      <li><code>methods.py</code></li>
    </ul>
  </li>

  <li>
    Make sure Python is installed (Python 3.9+ recommended).
  </li>

  <li>
    Install the required dependencies:
    <pre><code>pip install selenium</code></pre>
  </li>

  <li>
    Run the automation:
    <pre><code>python main.py</code></pre>
  </li>
</ol>

## Demo Video (Python)

https://github.com/user-attachments/assets/1c0b75af-911a-4d7d-8fb2-8bd9e53ac645

[Watch Demo Video: https://github.com/madgepereira020701/Demoblaze-Ecommerce-selenium-tutorial/blob/python/ProgramRunInPython_DemoblazeSeleniumTutorial_madgepereira020701.mp4](https://github.com/madgepereira020701/Demoblaze-Ecommerce-selenium-tutorial/blob/python/ProgramRunInPython_DemoblazeSeleniumTutorial_madgepereira020701.mp4)
