# React Read More Less

[![NPM](https://nodei.co/npm/react-read-more-less.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/react-read-more-less/)
[![npm version](https://badge.fury.io/js/react-read-more-less.svg)](https://badge.fury.io/js/react-read-more-less)
![license-isc](https://img.shields.io/github/license/Thamodaran/react-read-more-less.svg)

## Install
```
npm install react-read-more-less --save

```
## Usage
```js
import ReadMoreAndLess from 'react-read-more-less';

class ReadMoreAndLessText extends Component {
    render() {
        return (
            <ReadMoreAndLess
                ref={this.ReadMore}
                className="read-more-content"
                charLimit={250}
                readMoreText="Read more"
                readLessText="Read less"
            >
                {Paragraph}
            </ReadMoreAndLess>
        );
    }
}
```

## PROPTYPES
| Prop | Type | Default |
| ---- | ---- | ------- |
| className | String |  |
| charLimit | integer | 150 |
| readMoreText | String | Read more |
| readLessText | String | Read less |
# react-read-more-less
