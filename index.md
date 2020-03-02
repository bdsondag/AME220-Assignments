<!Doctype html>
<html>
  <head style="font-size:120px">
  <style>
  * {
	font-family: Arial, sans;
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	-moz-box-sizing: border-box;
}
#container {
    margin: 0 auto;
    width: 100%;
}
#accordion input {
	display: none;
}
#accordion label {
	background: darkgrey;
	border-radius: .25em;
	cursor: pointer;
	display: block;
	margin-bottom: .125em;
	padding: .25em 1em;
	z-index: 20;
  text-align: center;
}
#accordion label:hover {
	background: lightGreen;
}

#accordion input:checked + label {
	background: purple;
	border-bottom-right-radius: 0;
	border-bottom-left-radius: 0;
	color: white;
	margin-bottom: 0;
}
#accordion article {
	background: #f7f7f7;
	height:0px;
	overflow:hidden;
	z-index:10;
}
#accordion article p {
	padding: 1em;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	border-bottom-left-radius: .25em;
	border-bottom-right-radius: .25em;
	height: auto;
	margin-bottom: .125em;
}

    header {
      color: lightGreen;
      text-align: center;
      text-transform: capitalize;
      top: 0px
      padding: 10px;
      background-color: #333;
    }
    body {
      background-color: #333;
    }
    ul.a {
      list-style-type: circle;
      display: block;
    }
    ol.b{
      list-style-type: upper-roman;
    }
    table {
      border-collapse: collapse;
      text-align: left;
      width: 100%;
    }
    th, td {
      border:2px solid darkblue;
      height: 25px;
      width: 50%;
    }
  </style>
  <body>
    <div id="container">
  <header>
    <h1>
        brian sondag
    </h1>
    <a href="https://imgur.com/fYd2Lgv"><img style="display: block; margin-left: auto; margin-right: auto; width: 30%;" src="https://i.imgur.com/fYd2Lgv.png" width="200px" title="source: imgur.com" /></a>
  </header>
  <section id="accordion">
			<div>
				<input type="checkbox" id="check-1" />
				<label for="check-1">Contact Information</label>
				<article>
    <ul style="list-style: none; text-align: center">
      <li><a title='i go to w3' target='_blank' href="https://www.w3schools.com">
        (602)615-9848
      </a></li>
      <li><a title='i go to asu homepage' target='_blank' href="https://webapp4.asu.edu/myasu/">
        bdsondag@gmail.com
      </li></a>
      <li><a title='i go to w3 tutorial' target='_blank' href="https://www.w3schools.com/css/tryit.asp?filename=trycss_table_width">
        3224 w Cavedale Dr. Phoenix AZ, 85083
      </a></li>
    </ul>
    </article>
  </div>
  <div>
				<input type="checkbox" id="check-2" />
				<label for="check-2">Objective</label>
				<article>
    <p>
       To obtain a position as a mamber in an organization that takes pride in it's professionalism and strives to become an industry leader with interest in growth opportunities and cooperation between personnel.
     </p>
   </article>
 </div>
 <div>
				<input type="checkbox" id="check-3" />
				<label for="check-3">Education</label>
				<article>
    <table>
      <tr>
        <th>School Year</th>
        <th>school</th>
      </tr>
      <tr>
        <td>2012 - 2015</td>
        <td>Deer Valley High School</td>
      </tr>
      <tr>
        <td>2015 - 2016</td>
        <td>Nordonia High School</td>
      </tr>
      <tr>
        <td>2018 Spring</td>
        <td>Glendale Community College</td>
      </tr>
      <tr>
        <td>2018 - current</td>
        <td>ASU</td>
      </tr>
    </table>
  </article>
</div>
<div>
				<input type="checkbox" id="check-4" />
				<label for="check-4">Job History</label>
				<article>
    <ul class="a">
    <li>
      <p> Target Hardlines: stocking shelves and helping customers </p>
    </li>
    <li>
      <p> Sigma: Assist with projects to help organize the product codes int the system </p>
    </li>
    </ul>
  </article>
</div>
<div>
				<input type="checkbox" id="check-5" />
				<label for="check-5">References</label>
				<article>
    <ol class="b">
      <li>
        1. Ingrid Sondag
      </li>
      <li>
        2. Shad Ashcroft
      </li>
      <li>
        3. Yvonne Bland
      </li>
    </ol>
  </article>
</div>
</body>
</html>
