# Sometype Mono

---

## Short Story
Sometype Mono is a free monospaced font family for coding and tabular layout which licensed under [the SIL OFL1.1](http://scripts.sil.org/OFL). Designed by  [Ryoichi Tsunekawa](http://dharmatype.com).  Consists of 6 styles so far.

---

## Long Story  

### About
Sometype Mono is a free monospaced font family for coding and tabular layout which can bu used for commercial purpose for free.  


### Styles
So far, Sometype Mono consists 6 style.  
Regular, _Italic_, (Medium, Medium Italic,) **bold**, ***Bold Italic*** .

### License
Sometype Mono is licensed under the SIL Open Font License v1.1 (<http://scripts.sil.org/OFL>)  
To view the copyright and specific terms and conditions please refer to [OFL.txt](https://github.com/dharmatype/Sometype-Mono/blob/master/OFL.txt)


### Authors
[Ryoichi Tsunekawa](http://dharmatype.com)  


### Support
Please support our free font project.
Our free fonts are free even for commercial use. You can use them without any purchases.
But we welcome your support for free font project.  
Please visit [http://dharmatype.com/support](http://dharmatype.com/support)

---

## Sample
### Lorem ipsum
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eget auctor dolor. Vivamus scelerisque gravida lorem, ut viverra nisi. **This is Bold** Aliquam fermentum nunc eget lectus mattis, nec fringilla quam interdum. Curabitur ligula mi, suscipit sit amet auctor vitae, accumsan sit amet neque. Ut turpis orci, euismod at nulla sed, pharetra porta eros. (_This is Italic_) Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec feugiat aliquam ipsum, eget elementum ante euismod vitae. ***This is BoldItalic*** Ut vitae placerat ante.

### Distinguishability
O o 0  I i L l ! 1 |  2 Z 5 S 6 b 8 B  # * ^ ~  ( { [  . , : ; " ' ’ `  

### Nice-Figures
0 1 2 3 4 5 6 7 8 9

### Syntax
```js
// Javascript code with syntax highlighting.
var gl;
var points;

window.onload = function init(){
    var canvas = document.getElementById( "gl-canvas" );
     gl = WebGLUtils.setupWebGL( canvas );    
     if ( !gl ) { alert( "WebGL isn't available" );
}        

// Three Vertices        

var vertices = [
        vec2( -1, -1 ),
        vec2(  0,  0.5 ),
        vec2(  1, -1 ),
		vec2(1,1)
];    
//  Configure WebGL   
//    
    gl.viewport( 0, 0, canvas.width, canvas.height );
    gl.clearColor( 1.0, 1.0, 1.0, 1.0 );   

//  Load shaders and initialize attribute buffers

    var program = initShaders( gl, "vertex-shader", "fragment-shader" );
    gl.useProgram( program );        

// Load the data into the GPU        

    var bufferId = gl.createBuffer();
    gl.bindBuffer( gl.ARRAY_BUFFER, bufferId );
    gl.bufferData( gl.ARRAY_BUFFER, flatten(vertices), gl.STATIC_DRAW );    
// Associate out shader variables with our data buffer

      var vPosition = gl.getAttribLocation( program, "vPosition" );
      gl.vertexAttribPointer( vPosition, 2, gl.FLOAT, false, 0, 0 );
      gl.enableVertexAttribArray( vPosition );    
      render();
};

function render() {
    gl.clear( gl.COLOR_BUFFER_BIT );
   gl.drawArrays( gl.TRIANGLE_STRIP, 0, 4 );
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

### Italic for quote and captions  
> This is a blockquote following a header.
> This is a blockquote following a header.
> When something is important enough, you do it even if the odds are not in your favor.


### Markdown Table  

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |


### Plain Text Table  
```
+--------------------------------------+-----------------+  
| Zero and Oh                          | 0 O o           |  
+--------------------------------------+-----------------+  
| Ai and El and One and Exclam and Bar | I i L l 1 ! |   |  
+--------------------------------------+-----------------+  
| Two and Ze                           | 2 Z z           |  
+--------------------------------------+-----------------+  
| Five and Es                          | 5 S s           |  
+--------------------------------------+-----------------+  
| Six and be and Eight and Be          | 6 b 8 B         |  
+--------------------------------------+-----------------+  
| parenthesis and brackets             | ( { [ ] } )     |  
+--------------------------------------+-----------------+  
| Signs and Marks                      | # * ^ ~         |  
+--------------------------------------+-----------------+  
| Punctuations                         | . , : ; " ' ’ ` |  
+--------------------------------------+-----------------+  
```

### Unordered list:

*   Item foo abcdef
*   Item bar ghijkl
*   Item baz mnopqr
*   Item zip stuvwx

### Ordered list:

1.  Item 2018 123 one
1.  Item 2019 456 two
1.  Item 2020 789 three
1.  Item 2021 012 four

### Nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item

### Images
![/assets/img/SometypeMono_001.png](/assets/img/SometypeMono_001.png)  
![/assets/img/SometypeMono_002.png](/assets/img/SometypeMono_002.png)  
![/assets/img/SometypeMono_005.png](/assets/img/SometypeMono_005.png)  
![/assets/img/SometypeMono_006.png](/assets/img/SometypeMono_006.png)  
![/assets/img/SometypeMono_003.png](/assets/img/SometypeMono_003.png)  
![/assets/img/SometypeMono_004.png](/assets/img/SometypeMono_004.png)  
![/assets/img/SometypeMono_007.png](/assets/img/SometypeMono_007.png)  
![/assets/img/SometypeMono_011.png](/assets/img/SometypeMono_011.png)  
![/assets/img/SometypeMono_008.png](/assets/img/SometypeMono_008.png)  
![/assets/img/SometypeMono_012.png](/assets/img/SometypeMono_012.png)  
![/assets/img/SometypeMono_009.png](/assets/img/SometypeMono_009.png)  
![/assets/img/SometypeMono_010.png](/assets/img/SometypeMono_010.png)  
