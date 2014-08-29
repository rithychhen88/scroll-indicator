scroll-indicator
================

Scrollbar Indicator is useful for lengthy webpages. It helps indentifying the current location on a giving page. The Scrollbar Indicator can also be used to navigate through the content of a page. It is really simple to set up.


					<h4>Dependencies</h4>
					<p>
						Scrollbar Indicator requires the following libraries: 
					</p>
					<ol>
						<li>
							The latest Jquery, which you can download from <a href="http://jquery.com/" target="_blank">here</a>.
						</li>
						<li>
							The latest jqueryUI, you can download from <a href="http://jqueryui.com/" target="_blank">here</a>.
						</li>
					</ol>
					<h4>Getting Started</h4>
					<p>Download the latest code from <a href="#">here</a></p>

					<h4>How to use Scrollbar Indicator</h4>

					<p>Include the following css files into the header</p>
					<p>
						<code>
							&lt;link href="http://example.com/css/jquery-ui.min.css" rel="stylesheet"&gt;
						</code>
					</p>
					<p>
						<code>
							&lt;link href="http://example.com/css/jquery-scrollbar-indicator.css" rel="stylesheet"&gt;
						</code>
					</p>
					<p>
						Include the javascript files into the page 
					</p>
					<p>
						<code>
							&lt;script src="http://example.com/js/jquery.min.js"&gt;&lt;/script&gt;
						</code>
					</p>
					<p>
						<code>
							&lt;script src="http://example.com/js/jquery-ui.js"&gt;&lt;/script&gt;
						</code>
					</p>
					<p>
						<code>
							&lt;script src="http://example.com/js/jquery-scrollbar-indicator.js"&gt;&lt;/script&gt;
						</code>
					</p>
					<p>HTML decoration for your images goes like this</p>
					<code>
						&lt;div id="scrollbar"&gt;&lt;/div&gt;
					</code>
					<p>Include the following near the end of the page or in a seperate javascript file</p>
					<p>
						<code>
							&lt;script type="text/javascript"&gt;<br/>
								&nbsp;&nbsp;&nbsp;&nbsp;$("#scrollbar").scrollbarIndicator();<br/>
							&lt;/script&gt;
						</code>
					</p>
					<h4>Initialization Options</h4>
					<p>The following are the initialization options and their default values</p>
					<p>
						<code>
							handleColor: "#556b2f"
						</code>
					</p>
					<p>
						<code>
							backgroundColor: "#e9e9e9"
						</code>
					</p>
					<p>
						<code>
							height: 400
						</code>
					</p>
					<p>You can override any of these values during initialization.</p>
					<p>
						<code>
							&lt;script type="text/javascript"&gt;<br/>
								&nbsp;&nbsp;&nbsp;&nbsp;$("#scrollbar").scrollbarIndicator({<br/>
									&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"handleColor": "pink",<br/>
									&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"backgroundColor": "yellow",<br/> 
									&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"height": 400<br/>
								&nbsp;&nbsp;&nbsp;&nbsp;});<br/>
							&lt;/script&gt;
						</code>
					</p>
