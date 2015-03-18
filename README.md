Online-Whiteboard
=================

BrainCert's flash-based whiteboard editor features a painting and drawing tool, highlighter, text editor, image library, LaTeX math equations, import graphics, draw shapes &amp; symbols, draw grids, wolfram alpha outputs, save snapshots, and a lot more.

A simple JavaScript API to embed BrainCert Whiteboard in your website.

[https://www.braincert.com/developer/whiteboard-api](https://www.braincert.com/developer/whiteboard-api)

BrainCert's standalone whiteboard can be easily integrated with any website with complete customization including your own logo, and theme. The free plan supports 2 active sessions.

![BrainCert Whiteboard API](https://www.braincert.com/images/whiteboard-api-front.jpg)


***

# Documentation

You can use the JavaScript API to embed BrainCert's flash-based Whiteboard in your website with your own logo and theme.

Put the following code anywhere in the HTML document:


        <script type="text/javascript" src="//www.braincert.com/whiteboard/braincert-wb.js"></script>
        <script type="text/javascript">
                bcwb.init({
                    apiKey: 'YOUR_API_KEY',
                    height:'1500',
                    width:'1500',
                    bgcolor:'#FFF',
                    logo:'LOGO_URL'
                });
               </script>
        <div id="wbplayer"> </div>



* **apiKey**	- Your API Key
* **height**	- Height in pixels
* **width**	- Width in pixels
* **bgcolor**	- Background color of the whiteboard HTML area
* **logo**	- Your logo URL


Here is an example code:

        <script type="text/javascript" src="//www.braincert.com/whiteboard/braincert-wb.js"></script>
        <script type="text/javascript">
                bcwb.init({
                    apiKey: '9CfBFlnxDjyR3Jqao',`
                    height:'1500',
                    width:'1500',
                    bgcolor:'#FFF',
                    logo:'https://www.braincert.org/images/bc-logo-bottom.png'
                });
               </script>
        <div id="wbplayer"> </div>


***

# Demo

Seeing is Believing! See a demonstration of our amazing online whiteboard.

Try out BrainCert whiteboard at [eduWeaver - free online whiteboard](http://www.eduweaver.com/).

***

# Get API Key

Generate your free [API key](https://www.braincert.com/app/whiteboard). Our free plan supports 2 active sessions.


***

BrainCert is a cloud-based e-learning platform, virtual classroom, and enterprise-ready online learning management system (LMS). A soup-to-nuts solution for students and instructors, BrainCert offers powerful tools to create (and take) online courses, tests, tutorials, and live classes.

[https://www.braincert.com](https://www.braincert.com)
