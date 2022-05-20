# Installation
> `npm install --save @types/react-vertical-timeline-component`

# Summary
This package contains type definitions for react-vertical-timeline-component (https://github.com/stephane-monnot/react-vertical-timeline).

# Details
Files were exported from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/react-vertical-timeline-component.
## [index.d.ts](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/react-vertical-timeline-component/index.d.ts)
````ts
// Type definitions for react-vertical-timeline-component 3.3
// Project: https://github.com/stephane-monnot/react-vertical-timeline, https://stephane-monnot.github.io/react-vertical-timeline
// Definitions by: Stéphane Monnot <https://github.com/stephane-monnot>
//                 Lukas Elmer <https://github.com/lukaselmer>
// Definitions: https://github.com/DefinitelyTyped/DefinitelyTyped
// TypeScript Version: 2.8

import * as React from "react";

export interface VerticalTimelineProps {
    animate?: boolean | undefined;
    children?: React.ReactNode;
    className?: string | undefined;
    layout?: '1-column' | '2-columns' | undefined;
    lineColor?: string | undefined;
}

export interface VerticalTimelineElementProps {
    children?: React.ReactNode;
    id?: string | undefined;
    className?: string | undefined;
    date?: string | undefined;
    dateClassName?: string | undefined;
    iconClassName?: string | undefined;
    iconOnClick?: (() => void) | undefined;
    iconStyle?: React.CSSProperties | undefined;
    icon?: React.ReactNode | undefined;
    intersectionObserverProps?: any;
    onTimelineElementClick?: (() => void) | undefined;
    position?: string | undefined;
    style?: React.CSSProperties | undefined;
    textClassName?: string | undefined;
    contentStyle?: React.CSSProperties | undefined;
    contentArrowStyle?: React.CSSProperties | undefined;
    visible?: boolean | undefined;
}

export class VerticalTimeline extends React.Component<VerticalTimelineProps> { }
export class VerticalTimelineElement extends React.Component<VerticalTimelineElementProps> { }

````

### Additional Details
 * Last updated: Tue, 25 Jan 2022 01:01:36 GMT
 * Dependencies: [@types/react](https://npmjs.com/package/@types/react)
 * Global values: none

# Credits
These definitions were written by [Stéphane Monnot](https://github.com/stephane-monnot), and [Lukas Elmer](https://github.com/lukaselmer).
