<template>
    <div id="flex_box">
    
        <hr>
        <h1 class="text-center">Flex Direction</h1>
        <div class="text-center"><i>The flex-direction property defines in which direction the container wants to stack the flex items.</i></div>
        <hr>

        <h3>: row</h3>
    
        <div class="flex-container fd-row">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: row-reverse <i>(but from right to left)</i></h3>
    
        <div class="flex-container fd-row-reverse">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: column</h3>
    
        <div class="flex-container fd-column">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: column-reverse <i>(but from bottom to top)</i></h3>
    
        <div class="flex-container fd-column-reverse">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <hr>
        <h1 class="text-center">Flex Wrap</h1>
        <div class="text-center"><i>The flex-wrap property specifies whether the flex items should wrap or not.</i></div>
        <hr>

        <h3>: no-wrap</h3>
    
        <div class="flex-container fw-nowrap">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: wrap</h3>
    
        <div class="flex-container fw-wrap">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: wrap-reverse</h3>
    
        <div class="flex-container fw-wrap-reverse">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>


        <hr>
        <h1 class="text-center">Justify Content</h1>
        <div class="text-center"><i> The justify-content property is used to align the flex items.</i></div>
        <hr>

        <h3>: flex-start</h3>

        <div class="flex-container fc-flex-start">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: flex-end</h3>

        <div class="flex-container fc-flex-end">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: space-around</h3>

        <div class="flex-container fc-space-around">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: space-between</h3>

        <div class="flex-container fc-space-between">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: center</h3>

        <div class="flex-container fc-center">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>


        <hr>
        <h1 class="text-center">Align Items</h1>
        <div class="text-center"><i> The align-items property is used to align the flex items vertically.</i></div>
        <hr>

        <h3>: stretch</h3>

        <div class="flex-container ai-stretch height-300">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: flex-start</h3>

        <div class="flex-container ai-flex-start height-300">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: flex-end</h3>

        <div class="flex-container ai-flex-end height-300">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <h3>: center</h3>

        <div class="flex-container ai-center height-300">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
        </div>

        <hr>
        <h1 class="text-center">Align Content</h1>
        <div class="text-center"><i>The align-content property is used to align the flex lines.</i></div>
        <hr>

        <h3>: stretch</h3>

        <div class="flex-container ac-stretch fw-wrap height-600">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>

        <h3>: space-between</h3>

        <div class="flex-container ac-space-between fw-wrap height-600">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>

        <h3>: space-around</h3>

        <div class="flex-container ac-space-around fw-wrap height-600">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>

        <h3>: center</h3>

        <div class="flex-container ac-center fw-wrap height-600">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>

        <h3>: flex-start</h3>

        <div class="flex-container ac-flex-start fw-wrap height-600">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>

        <h3>: flex-end</h3>

        <div class="flex-container ac-flex-end fw-wrap height-600">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>
            <div class="item">9</div>
            <div class="item">10</div>
            <div class="item">11</div>
            <div class="item">12</div>
        </div>

        <hr>
        <h1 class="text-center">BONUS</h1>
        <hr>

        <div class="flex-container">
            <div class="item item-bonus" style="width: 300px; line-height: inherit;">
                <div class="box-1"></div>
            </div>
            <div class="item" style="width: 600px; line-height: inherit;">
                Contrary to popular belief, Lorem Ipsum is not simply random text. 
                    It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. 
                    Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, 
                    looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, 
                    and going through the cites of the word in classical literature, discovered the undoubtable source. 
                    Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" 
                    (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. 
                    The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.
            </div>
        </div>

        <hr>
        <h1 class="text-center">Child Elements (Items)</h1>
        <hr>

        <h3>: order</h3>

        <div class="flex-container">
            <div class="item" style="order: 3">1</div>
            <div class="item" style="order: 2">2</div>
            <div class="item" style="order: 4">3</div> 
            <div class="item" style="order: 1">4</div>
        </div>

        <h3>: flex-grow</h3>

        <div class="flex-container">
            <div class="item">1</div>
            <div class="item" style="flex-grow: 1">2</div>
            <div class="item" style="flex-grow: 2">3</div> 
        </div>

        <h3>: flex-shrink</h3>

        <div class="flex-container">
            <div class="item" style="width: 300px">1</div>
            <div class="item" style="width: 300px; flex-shrink: 2">2</div>
            <div class="item" style="width: 300px">3</div> 
        </div>

        <h3>: flex-basis</h3>

        <div class="flex-container">
            <div class="item">1</div>
            <div class="item" style="flex-basis: 500px">2</div>
            <div class="item">3</div> 
        </div>

        <h3>: flex</h3>

        <div class="flex-container">
            <div class="item">1</div>
            <div class="item" style="flex: 0 0 300px;">2</div>
            <div class="item">3</div> 
        </div>

        <h3>: align-self</h3>

        <div class="flex-container height-300">
            <div class="item">1</div>
            <div class="item" style="align-self: center;">2</div>
            <div class="item">3</div> 
        </div>
    
    </div>
</template>

<style scoped>
    .item-bonus {
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .box-1 {
        width: 100px;
        height: 100px;
        background: red;
    }
    .ac-stretch {
        align-content: stretch;
    }
    .ac-flex-end {
        align-content: flex-end;
    }
    .ac-flex-start {
        align-content: flex-start;
    }
    .ac-center {
        align-content: center;
    }
    .ac-space-around {
        align-content: space-around;
    }
    .ac-space-between {
        align-content: space-between;
    }
    .ai-stretch {
        align-items: stretch;
    }
    .ai-flex-start {
        align-items: flex-start;
    }
    .ai-flex-end {
        align-items: flex-end;
    }
    .ai-center {
        align-items: center;
    }
    .fc-center {
        justify-content: center;
    }
    .fc-space-between {
        justify-content: space-between;
    }
    .fc-space-around {
        justify-content: space-around;
    }
    .fc-flex-start {
        justify-content: flex-start;
    }
    .fc-flex-end {
        justify-content: flex-end;
    }
    .text-center {
        text-align: center;
    } 
    .flex-container {
        display: flex;
        background-color: blue;
    }
    .flex-container .item {
        background-color: #f1f1f1;
        width: 100px;
        margin: 10px;
        text-align: center;
        line-height: 75px;
        font-size: 30px;
    }
    .fd-row {
        flex-direction: row;
    }
    .fd-column {
        flex-direction: column;
    }
    .fd-row-reverse {
        flex-direction: row-reverse;
    }
    .fd-column-reverse {
        flex-direction: column-reverse;
    }
    .fw-wrap {
        flex-wrap: wrap;
    }
    .fw-nowrap {
        flex-wrap: nowrap;
    }
    .fw-wrap-reverse {
        flex-wrap: wrap-reverse;
    }
    .height-300 {
        height: 300px;
    }
    .height-600 {
        height: 600px;
    }
</style>

