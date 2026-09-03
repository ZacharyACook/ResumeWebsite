<div class = container>
    <a class="projectNum1" href="https://github.com" target="_blank" rel="noopener noreferrer">
        <div class = textBox>
            <div class = textStyle>
                <h1>Project 1</h1>
            
            </div>
        </div>
    </a>    
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
  position: relative;
  left: -2%;
  top: -65%;
  width: 500px;
  height: 65px;
  border-radius: 20px;
  padding: 1rem;
  z-index: 2;
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

.projectNum1 {
  background: #494a52;
  position: relative;
  top: 15px;
  width: 500px;
  height: 65px;
  border-radius: 20px;
  padding: 1rem;
  z-index: 1;
  /* Prevent shrinking when zooming out */
  flex-shrink: 0;
}

.projectNum1:hover {
background: #262a4a
}
</style>