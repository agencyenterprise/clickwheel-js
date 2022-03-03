# clickwheel.js

Source code at https://github.com/agencyenterprise/clickwheel-js

## Installation

    npm install --save clickwheel-js

or

    yarn add clickwheel-js

## Usage

```
import React from 'react';
import ClickWheel from 'clickwheel-js';

function Demo(){
    return(
        <React.Fragment>
            <div id="wrapper">
                <ClickWheel
                    scrollerId="wrapper"
                    onCenterClick={() => console.log('onCenterClick')}
                    onMenuClick={() => console.log('onMenuClick')}
                    onPlayPause={() => console.log('onPlayPauseClick')}
                    onNext={() => console.log('onNextClick')}
                    onPrevious={() => console.log('onPreviousClick')}
                />
            </div>
        </React.Fragment>
    )
}

export default Demo;
```

## Props

| Name          | Type     | required |
| ------------- | -------- | -------- |
| scrollerId    | string   | yes      |
| onCenterClick | function | no       |
| onMenuClick   | function | no       |
| onPlayPause   | function | no       |
| onNext        | function | no       |
| onPrevious    | function | no       |
