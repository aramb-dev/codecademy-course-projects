# Previously: New York City Blog
<h2>WEB DEVELOPMENT FOUNDATIONS</h2>
<h3>New York City Blog</h3>
<p>After researching New York City, you decide to create a blog for your viewers who want to know more about the city. It’s time to create a blog to show off how amazing the Big Apple is. You got this!</p>
<p>Don’t forget to save your code after each step. By pressing save to run your code you will see the changes you’ve made in the browser.</p>
<p>Note: While you are developing the webpage, you will notice that the elements are automatically assigned colors, borders, and positioned properly. This is because of the CSS file. Don’t worry about CSS right now, it’s only there so that the webpage looks nice.</p>
<h4>Tasks</h4>
<ol>
  <li>
    <input type="checkbox" checked> Mark the tasks as complete by checking them off
  </li>
</ol>
<h4>Navigation Bar</h4>
<ol>
  <li>Create a <code>&lt;nav&gt;</code> element underneath the opening <code>&lt;body&gt;</code> tag.</li>
  <li>
    <p>Within the <code>&lt;nav&gt;</code> element, create a <code>&lt;ul&gt;</code> element to create an unordered list.</p>
    <p>The unordered list should contain the following three items:</p>
    <ul>
      <li><code>Blog</code></li>
      <li><code>Media</code></li>
      <li><code>About</code></li>
    </ul>
    <p>Use an <code>&lt;li&gt;</code> element with <code>&lt;a href=""&gt;&lt;/a&gt;</code> nested within the <code>&lt;li&gt;</code> element to link the content to the nav bar. You may notice that the navbar doesn’t work right now, but don’t worry, once the content is added, the navbar will be fully functional!</p>
  </li>
</ol>
<h4>Blog Content</h4>
<ol start="3">
  <li>
    <p>You need to title your blog, so people know what you’re writing about. Create a <code>&lt;header&gt;</code> element under the closing <code>&lt;/nav&gt;</code> tag.</p>
    <p>Within the <code>&lt;header&gt;</code> element, create an <code>&lt;h1&gt;</code> element which should contain the following:</p>
    <p>New York City</p>
  </li>
  <li>
    <p>Create a <code>&lt;main&gt;</code> element below the closing <code>&lt;/header&gt;</code> tag.</p>
    <p>Within the <code>&lt;main&gt;</code> element, create a <code>&lt;section&gt;</code> element with an id of “blog”.</p>
    <p>This <code>&lt;section&gt;</code> element will hold the main content of your webpage. You are giving this element an id so that you can target it with the nav bar.</p>
  </li>
  <li>
    <p>Create an <code>&lt;article&gt;</code> element within the <code>&lt;section&gt;</code> element.</p>
    <p>Then, create a <code>&lt;p&gt;</code> element within <code>&lt;article&gt;</code> that has the following:</p>
    <p>New York City is made up of five boroughs which include Queens, Manhattan, Brooklyn, the Bronx, and Staten Island. The city is the home of approximately 8 million people. In 1876, France gifted the City of New York what is known as the Statue of Liberty, which is currently located on Liberty Island and commonly visited by tourists. However, it took 10 years to assemble and therefore wasn’t unveiled until 1886. Another tourist destination is Times Square. Times Square is commonly known for the big buildings, Broadway shows, and bright neon signs. This famous location was named after The New York Times after the Times moved to that location. Prior to that, it was named Longacre Square. New York City is also known for its bridges that connect the boroughs and allow ease of transportation.</p>
  </li>
  <li>
    <p>Now that our blog has some content, the next step is adding media to enhance our blog.</p>
    <p>You can do this by using the <code>&lt;figure&gt;</code> element. Under the closing <code>&lt;/section&gt;</code> tag, create a <code>&lt;figure&gt;</code> element.</p>
  </li>
  <li>
    <p>Create an <code>&lt;img&gt;</code> tag within <code>&lt;figure&gt;</code> and use the following link as the src:</p>
    <p><code>https://content.codecademy.com/courses/Semantic%20HTML/statue-of-liberty.jpeg</code></p>
  </li>
  <li>
    <p>Let’s describe the image for those who don’t know what statue this is!</p>
    <p>Using <code>&lt;figcaption&gt;</code> add this description of the image:</p>
    <p>This is the Statue of Liberty, a popular tourist attraction located on Liberty Island.</p>
  </li>
</ol>
<h4>Aside Content</h4>
<ol start="9">
  <li>
    <p>For our blog post, you need to add additional content to enhance the post, you can do this by using the <code>&lt;aside&gt;</code> element.</p>
    <p>Under the closing <code>&lt;/figure&gt;</code> tag, create an <code>&lt;aside&gt;</code> element.</p>
    <p>Within <code>&lt;aside&gt;</code>, create a <code>&lt;p&gt;</code> element containing the following information:</p>
    <p>New York City is very popular for the variety of great food it has. Some of the top food items in NYC include:</p>
  </li>
  <li>
    <p>New York is known for its amazing food. Our blog should list some of the top food options in NYC. You can do this by creating an ordered list!</p>
    <p>Create an ordered list by using the <code>&lt;ol&gt;</code> element within the <code>&lt;aside&gt;</code> element. In an ordered list, the first item is ranked one, the second item is ranked two, and so on.</p>
    <p>The ordered list should contain the following seven items in this order:</p>
    <ol>
      <li>Pizza</li>
      <li>Bagels</li>
      <li>Burgers and Sandwiches</li>
      <li>Ramen</li>
      <li>Tacos</li>
      <li>Pasta</li>
      <li>Desserts</li>
    </ol>
  </li>
</ol>
<h4>Media</h4>
<ol start="11">
  <li>
    <p>Right now our blog post consists of only one image. Adding more media can help give a better visual representation of New York. Let’s create a section for the media content.</p>
    <p>Create a <code>&lt;section&gt;</code> element with an id of “media” under the closing <code>&lt;/aside&gt;</code> tag.</p>
    <p>Within the new <code>&lt;section&gt;</code> element, create an <code>&lt;article&gt;</code> element.</p>
    <p>Then, create an <code>&lt;h2&gt;</code> element within <code>&lt;article&gt;</code> that says:</p>
    <p>The Scenery in NYC</p>
  </li>
  <li>
    <p>You are going to add a little description to explain the media. Add a <code>&lt;p&gt;</code> element directly underneath the closing <code>&lt;/h2&gt;</code> tag but within the <code>&lt;article&gt;</code> element with the following paragraph:</p>
    <p>While the view in the city is beautiful, the sounds are not as lovely. Below you'll see an example of the view and the sounds you'll deal with in NYC on a daily basis.</p>
  </li>
  <li>
    <p>New York City has a beautiful skyline, so let’s show that with a video.</p>
    <p>Under the closing <code>&lt;/article&gt;</code> tag, create a <code>&lt;video&gt;</code> element with the attribute controls. Use the following URL as the src: "https://content.codecademy.com/courses/Semantic%20HTML/nyc-skyline-timelapse.mp4".</p>
  </li>
  <li>
    <p>During the night time, the New York City skyline can light up the whole sky! This time you are going to use <code>&lt;embed&gt;</code> to display an image of the skyline.</p>
    <p>Create an <code>&lt;embed&gt;</code> element under the closing <code>&lt;/video&gt;</code> tag. Use the following URL as the src: "https://content.codecademy.com/courses/Semantic%20HTML/nyc-skyline.jpeg".</p>
  </li>
  <li>
    <p>New York City is known as “the city that never sleeps.” At any point in the day, you can hear the traffic as you make your way through the city. Let’s add an audio clip to show how loud NYC can be.</p>
    <p>Create an <code>&lt;audio&gt;</code> tag with the attribute controls directly below the <code>&lt;embed&gt;</code> element. (Don’t forget the closing tag.)</p>
    <p>Inside the <code>&lt;audio&gt;</code> tag, insert an audio file with the following URL as the src: "https://content.codecademy.com/courses/Semantic%20HTML/nyc-sounds.mov".</p>
  </li>
</ol>
<h4>Footer</h4>
<ol start="16">
  <li>
    <p>At the bottom of a page, you can add a footer to credit you for the creation of this blog!</p>
    <p>Create a <code>&lt;footer&gt;</code> element with an id of “about” under the closing <code>&lt;/section&gt;</code> tag.</p>
    <p>Within the <code>&lt;footer&gt;</code> element, create an <code>&lt;p&gt;</code> element that says:</p>
    <p>Created by [Your Name]</p>
  </li>
</ol>


# NEW: Riyadh Saudi Arabia Blog

<h2>WEB DEVELOPMENT FOUNDATIONS</h2>
<h3>Riyadh, Saudi Arabia Blog</h3>

<p>After researching Riyadh, Saudi Arabia, you decide to create a blog for your viewers who want to know more about the city. It’s time to create a blog to showcase the beauty and culture of Riyadh. You got this!</p>
<p>Don’t forget to save your code after each step. By pressing save to run your code you will see the changes you’ve made in the browser.</p>
<p>Note: While you are developing the webpage, you will notice that the elements are automatically assigned colors, borders, and positioned properly. This is because of the CSS file. Don’t worry about CSS right now, it’s only there so that the webpage looks nice.</p>

<h4>Tasks</h4>
<p>17/17 Complete</p>

<h4>Navigation Bar</h4>
<ol>
  <li>Create a &lt;nav&gt; element underneath the opening &lt;body&gt; tag.</li>
  <li>Within the &lt;nav&gt; element, create a &lt;ul&gt; element to create an unordered list.</li>
  <li>The unordered list should contain the following three items:</li>
  <ul>
    <li>Blog</li>
    <li>Media</li>
    <li>About</li>
  </ul>
  <li>Use an &lt;li&gt; element with &lt;a href=""&gt;&lt;/a&gt; nested within the &lt;li&gt; element to link the content to the nav bar. You may notice that the navbar doesn’t work right now but don’t worry, once the content is added, the navbar will be fully functional!</li>
  <li>Note: Save your work to see your progress.</li>
</ol>

<h4>Blog Content</h4>
<ol start="5">
  <li>You need to title your blog, so people know what you’re writing about. Create a &lt;header&gt; element under the closing &lt;/nav&gt; tag.</li>
  <li>Within the &lt;header&gt; element, create an &lt;h1&gt; element which should contain the following:</li>
  <ul>
    <li>Riyadh, Saudi Arabia</li>
  </ul>
  <li>Create a &lt;main&gt; element below the closing &lt;/header&gt; tag.</li>
  <li>Within the &lt;main&gt; element, create a &lt;section&gt; element with an id of “blog”.</li>
  <li>This &lt;section&gt; element will hold the main content of your webpage. You are giving this element an id so that you can target it with the nav bar.</li>
  <li>Create an &lt;article&gt; element within the &lt;section&gt; element.</li>
  <li>Then, create a &lt;p&gt; element within &lt;article&gt; that has the following:</li>
  <ul>
    <li>Riyadh, the capital of Saudi Arabia, is a vibrant city with a rich cultural heritage. It is known for its modern architecture, bustling souks (markets), and delicious cuisine. With its fascinating history and warm hospitality, Riyadh offers a unique and unforgettable experience for visitors. In this blog, we will explore the top attractions, local cuisine, and cultural highlights of Riyadh.</li>
  </ul>
  <li>Note: Save your work to see your progress.</li>
</ol>

<h4>Aside Content</h4>
<ol start="12">
  <li>For our blog post, you need to add additional content to enhance the post, you can do this by using the &lt;aside&gt; element.</li>
  <li>Under the closing &lt;/figure&gt; tag create an &lt;aside&gt; element.</li>
  <li>Within &lt;aside&gt;, create a &lt;p&gt; element containing the following information:</li>
  <ul>
    <li>Riyadh is famous for its traditional food, which reflects the rich flavors and spices of Arabian cuisine.</li>
  </ul>
  <li>Saudi Arabian cuisine is diverse and delicious. Our blog should list some of the popular food options in Riyadh. You can do this by creating an ordered list!</li>
  <li>Create an ordered list by using the &lt;ol&gt; element within the &lt;aside&gt; element. In an ordered list, the first item is ranked one, the second item is ranked two, and so on.</li>
  <li>The ordered list should contain the following six items in this order:</li>
  <ol>
    <li>Kabsa</li>
    <li>Mandi</li>
    <li>Mutabbaq</li>
    <li>Shawarma</li>
    <li>Falafel</li>
    <li>Luqaimat</li>
  </ol>
  <li>Note: Save your work to see your progress.</li>
</ol>

<h4>Media</h4>
<ol start="18">
  <li>Right now, our blog post consists of only one image. Adding more media can help give a better visual representation of Riyadh. Let’s create a section for the media content.</li>
  <li>Create a &lt;section&gt; element with an id of “media” under the closing &lt;/aside&gt; tag.</li>
  <li>Within the new &lt;section&gt; element, create an &lt;article&gt; element.</li>
  <li>Then, create an &lt;h2&gt; element within &lt;article&gt; that says:</li>
  <ul>
    <li>Discover Riyadh Through Photos</li>
  </ul>
  <li>You are going to add a little description to explain the media. Add a &lt;p&gt; element directly underneath the closing &lt;/h2&gt; tag but within the &lt;article&gt; element with the following paragraph:</li>
  <ul>
    <li>Experience the beauty and diversity of Riyadh through these captivating photographs. From historical landmarks to modern attractions, these photos showcase the essence of this enchanting city.</li>
  </ul>
  <li>Riyadh is home to many iconic landmarks. Let’s display some of these landmarks with a gallery of images.</li>
  <li>Under the closing &lt;/article&gt; tag, create a &lt;figure&gt; element.</li>
  <li>Within the &lt;figure&gt; element, create four &lt;img&gt; tags. Use the provided links as the src for each image.</li>
  <ul>
    <li>Image 1: https://content.codecademy.com/courses/Semantic%20HTML/riyadh-landmark-1.jpeg</li>
    <li>Image 2: https://content.codecademy.com/courses/Semantic%20HTML/riyadh-landmark-2.jpeg</li>
    <li>Image 3: https://content.codecademy.com/courses/Semantic%20HTML/riyadh-landmark-3.jpeg</li>
    <li>Image 4: https://content.codecademy.com/courses/Semantic%20HTML/riyadh-landmark-4.jpeg</li>
  </ul>
  Add <code>&ltfigcaption&gt</code> Caption for each of these images:
  <ol>
    <li>The stunning Kingdom Centre Tower, one of Riyadh’s most iconic skyscrapers.</li>
    <li>The historic Diriyah Gate, a UNESCO World Heritage Site and symbol of Saudi Arabia’s rich heritage.</li>
    <li>The vibrant Souq Al Zal, a traditional market offering a wide range of local products and goods.</li>
    <li>The captivating King Fahd Fountain, the world’s tallest water fountain located in Jeddah. </li>
    
  </ol>
  <li>Note: Save your work to see your progress.</li>
</ol>

<h4>About</h4>
<ol start="27">
  <li>Now, let’s create the final section of our webpage, the “About” section.</li>
  <li>Create a &lt;section&gt; element with an id of “about” under the closing &lt;/figure&gt; tag.</li>
  <li>Within the new &lt;section&gt; element, create an &lt;article&gt; element.</li>
  <li>Then, create an &lt;h2&gt; element within &lt;article&gt; that says:</li>
  <ul>
    <li>About Riyadh</li>
  </ul>
  <li>To give a brief description of Riyadh, create a &lt;p&gt; element directly underneath the closing &lt;/h2&gt; tag but within the &lt;article&gt; element with the following paragraph:</li>
  <ul>
    <li>Riyadh, the capital city of Saudi Arabia, is a bustling metropolis and the largest city in the country. It is a major cultural, political, and economic hub, attracting visitors from around the world. Riyadh offers a unique blend of traditional Arabian heritage and modern development, making it an exciting destination for travelers.</li>
  </ul>
  <li>Note: Save your work to see your progress.</li>
</ol>

<h4>Footer</h4>
<ol start="34">
  <li>We’re almost there! Let’s create the final section of our webpage, the footer.</li>
  <li>Create a &lt;footer&gt; element under the closing &lt;/section&gt; tag of the “about” section.</li>
  <li>Within the &lt;footer&gt; element, create a &lt;p&gt; element containing the following information:</li>
  <ul>
    <li>&copy; 2023 Riyadh Blog. All rights reserved.</li>
  </ul>
  <li>Note: Save your work to see your progress.</li>
</ol>

