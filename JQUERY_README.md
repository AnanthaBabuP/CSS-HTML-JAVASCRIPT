# CSS-HTML-JAVASCRIPT
Day to day Learning

JQUERY 

PART-1:
    1.JQuery Introduction
    2.JQuery Feauture:
        1.simple and easy to learn
        2.Light Weight
        3.css Manipuation
        4.Html manipulation
        5.Dom Traversal and Manipualtion
        6.Cross browser support
        7.Event Handling
        8.JavaScript Library
    3.Add JQUERY
        1.Download From www.jquery.com
        2.Includ JQuery from a CDN(Content Delevery Network)
    4. Add jquery on web-page
        <head>
            <script src="jquery-1.11.3.js"></script>
        </head>
    
    5.JQuery CDN
        1. CDN-Content Delivery (or)  Distribution Network
        2. Here Lot of files are stored,using CDN you can directly use  these files on your website,no need to upload these files on your server. 
        3.TypeTo Implement CDN For:
            1. Google CDN: https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js
            2. Microsoft CDN: https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.6.0.min.js
            3. CDNJS: https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js
            4. jsDelivr: https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.min.js
    6. Advantages of using CDN?
        1.It reduce the load from your server.
        2.It saves bandwidth.
        When any User visit on other website it save in browser, as a result next time easy to load.
    7.Editiors for JQuery:
        (Notepad,++,VSCode,CKEditior,TinyMCE,etc..)

    8. JQuery Syntax
        $(selector).action();

        Example:
            $('.input1').hide(); 
    9. What is dollar Sign ($) in JQUERY?  
        synt:
            $(document).ready(function(){

            });
                    (or)
            JQuery(document).ready(function(){

            });
    10. Document Ready Event:
        You can notice in any Jquery example or code jquery methods are inside document ready Event.

        syntax:
            $(document).ready(function(){
                // Jquery Methods
            });
    
    11. Downloading JQuery:
        Versions:
            1.Product Version - Complite Version
            2. Development Version  - developer Vaersion
    12.GoogleCDN-Example

PART-2:
    1. Microsoft CDN-Exapmle
    2. JQuery CDN-Example
    3. DeveloperCDN - Example

PART-3:
    1.Element Selector
    2. Event handling
        1.Mouse Event 
        2.Keyboard Event
        3.Form Event
        4.Windows Event
    3. DOM Manipulation Methods
        1.append()
        2.before()
        3.after()
        4.prepend()
        5.remove()
        6.replaceAll()
        7.wrap()

PART-4:
    1.Mainpulate the HTML Attributes
        1.attr()
        2.prop()
        3.html()
        4.text()
        5.val()
    2. syntax:
        $('selector').attr('name','value');
        $('selector').prop('name','value');  
        $('selector').html('content');  
        $('selector').text('content'); 
        $('selector').val('content');
    3. Calculator Program

PART-5:
    1.manipulate HTML Element's Dimenstions
        1.height()
        2.innerHeight()
        3.outerHeight()
        4.offset()
        5.position()
        6.width()
        7.innerWidth()
        8.outerWidth()
    2.Syntex:
        1.$('selector').height('value');
        2.$('selector').innerHeight('value');
        3.$('selector').outerHeight('value');
        4.$('selector').offset('value');
        5.$('selector').position('value');
        6.$('selector').width('value');
        7.$('selector').innerWidth('value');
        8.$('selector').outerWidth('value');
    
    3.The Following table lists jQuery methods for traversal DOM Element
        1.children()
        2.each()
        3.find()
        4.first()
        5.next()
        6.parent()
        7.prev()
        8.siblings()
    4.Syntex:
        1.$('selector').each(CallBack Function);
        2.$('selector').children();
        3.$('selector').find('selector to find child');
        4.$('selector').next();
        5.$('selector').parent();
        6.$('selector').siblings();

PART-6:
    1.CSS Manipulation:
        1.css()
        2.addClass()
        3.hasClass()
        4.removeClass()
        5.toggleClass()
       Syntex:
        1.$('selector').css({
            'style Property Name':'value',
        });
        2.$('selector').addClass('css class Name');
        3.$('selector').toggleClass('css class Name');
    
    3.JQuerey Animation:
        1.animate()
        2.queue()
        3.stop()
        4.fedeln()
        5.fadeOut()
        6.fadeTo()
        7.fadeToggle()
        8.hide()
        9.show()
        10.toggle()
        11.slideUp()
        12.slideDown()
        13.slideToggle() 
       
       Animated syntex:
        1.$('selector').animate(
            {'stylepropertyname':'value'},
            duration,
            easing,
            callback
            ); 
                (or)
        $('selector').animate({'propertyName':'value'},{Options})
    
    2.Set Animation Duration
        $('img').animate({
            height:'100px',
            width:'100px'
        },5000);

    3.Apply Easing Method
        1.linear
        2.swing

        $('img').animate({
            height:'100px',
            width:'100px'
        },5000,'swing')
    4.callback Function on Animation Complete
        $('img').animate({
            height:'100px',
            width:'100px'
        },5000,function(){
            $('msg').text('Animating Complited...)
        });

        <img src='sample.jpg'></img>
        <p id='msg'></p>
    5. Specify Animation Options
            You can specify various options as JSON Object.
            The option include duration,easing.queue,step,progress,complite,start,done and always.
    
    6.syntex:
        1. $('selector').queue(); -show or manipulate the queue
        2. $('selector').fadeIn(speed,easing,callback); -fading to clear
        3. $('selector').fadeIn(speed,easing,callback); -clear to fading
        $('selector').hide(speed,easing,callback);
        $('selector').show(speed,easing,callback);
        $('selector').toggle(speed,easing,callback);

PART-7:
    1.JQUery Animation1 - Example
    2.JQuery Event Methods
        1.form Event
        2.Keyboard Event
        3.Mouse Event
        4.Browser Event
        5.Document Loading
        
        1.Form Event Methods():

            JQuery Event - DOM Event
            1.blur       - onBlur
            2.change     - onchange
            3.focus      - onFocus
            4.focusin    - onFocusin
            5.select     - onSelect
            6.submit     - onSubmit    
        
        2.Keyboard Event
            1.keydown    - onKeydown
            2.keyUp      - onKeyUp
            3.keyPress   - onKeyPress
            3.focusOut   -

        3.Mouse Evnet
            1. click
            2. dblclick
            3. focusout
            4. hover
            5. mousedown
            6. mouseenter
            7. mouseleave
            8. mousemove
            9. mouseout
            10.mouseover
            11.mouseup
            12.toggle
        4.Browser Event Methods()
            1.Error
            2.Resize
            3.scroll
        5.Document loading Methods():
            1.load
            2.ready
            3.unload

PART-8:
    1.Event Object:
        1.JQuery Passes an event object to every event handler function.
            1.target
            2.pageX
            3.pageY
            4.related Target..etc..
    2.this Keyword in Event Handler
    3.Hover()
        1.mouseenter,mouseleave,etc...
    4.Event Binding Using on()
        synt:
            on(type,selector,data,fn);
    5.Event Binding Multiple Elements:
        example:
            $('#myDiv').on('mouseenter mouseleave)',function(){
                $('myDiv').text('The Mouse entered or left from the div');
            });

            <div id='myDiv' style='width:100px;height=100px;'></div>
    6.Specify Named function as Event Handler
        ex:$('#myDiv').on('mouseenter',namedFunction);
            var namedFunction = function(){
                alert('The Mouse Entered!');
            }
    7.Event Bubbling