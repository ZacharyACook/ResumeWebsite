

<div class = container>
    <div class = textBox>
        <div class = textStyle>    
            Hello, my name is Zach, and this is my resume website.
            I am an 18-year-old college student who is interested in programming and cybersecurity.
            The overall purpose of this website is to show off and organize all the cybersecurity projects
            I have worked on so far. 
        </div>  
    </div>

    <div class = textBox style = "height: 300px; position:fixed; left: 35rem; top: 6.5rem">
        <div class = textStyle>    
            <h1>Education:</h1>
            <div style="font-style:italic">Grand Oaks Highschool -- 2022-2026 </div>
            <div style="font-style:italic">East Texas A&M -- 2026-2030</div>
            {"- - - - - - - - - - - - - - - - - - - - - - - - - - - - - "}
            <h1>Certifications:</h1>
            <div style="font-style:italic">COMPTIA Security+ -- 2025-2028</div>
        </div>    
    </div>
</div> 


<style>
.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 2rem;
  gap: 2rem;

  /* Prevent weird zoom-out collapsing */
  flex-wrap: nowrap;
}

.textBox {
  background: #818479;
  width: 500px;
  height: 400px;
  border-radius: 20px;
  padding: 1rem;
  /* Prevent shrinking when zooming out */
  flex-shrink: 0;
}

.textStyle {
  flex: 1;               /* Take remaining space */
  min-width: 300px;      /* Prevent collapsing */
  font-size: 1.5rem;
  font-weight: bold;
  color: #E9F1F7;
}

</style>