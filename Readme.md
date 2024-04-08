# [ClickWheelJS.com](https://clickwheeljs.com)

Source code [here](https://github.com/agencyenterprise/clickwheel-js)

## Maker

Made with <3 by [AE Studio](https://ae.studio?utm_source=sds&utm_medium=referral&utm_campaign=clickwheeljs&utm_content=logo&utm_term=3ff5251a-e107-4d47-bfb8-b2962debd252)

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
