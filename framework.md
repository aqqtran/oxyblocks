See the framework in action [here](https://oxyblocks.com/framework)!
> All values can be customised in the Framework page when you first import a design set

---

# Breakpoints
| Normal | Large  | Medium | Small | Extra small |
|--------|--------|--------|-------|-------------|
| All    | 1400px | 992px  | 768px | 480px       |
> These values can be changed in the Oxygen editor

---

# Grid
## Display
| Class  | Property       |
|--------|----------------|
| o-grid | display: grid;<br> |

## Columns
| Normal         | Large           | Medium          | Small           | Extra small      | Properties                                       |
|----------------|-----------------|-----------------|-----------------|------------------|--------------------------------------------------|
| o-grid-cols-2  | o-grid-cols-l-1 | o-grid-cols-m-1 | o-grid-cols-s-1 | o-grid-cols-xs-1 | grid-template-columns: repeat(2,minmax(0,1fr));<br>  |
| o-grid-cols-3  | o-grid-cols-l-2 | o-grid-cols-m-2 | o-grid-cols-s-2 |                  | grid-template-columns: repeat(3,minmax(0,1fr));<br>  |
| o-grid-cols-4  | o-grid-cols-l-3 | o-grid-cols-m-3 | o-grid-cols-s-3 |                  | grid-template-columns: repeat(4,minmax(0,1fr));<br>  |
| o-grid-cols-5  | o-grid-cols-l-4 | o-grid-cols-m-4 |                 |                  | grid-template-columns: repeat(5,minmax(0,1fr));<br>  |
| o-grid-cols-6  | o-grid-cols-l-5 |                 |                 |                  | grid-template-columns: repeat(6,minmax(0,1fr));<br>  |
| o-grid-cols-7  | o-grid-cols-l-6 |                 |                 |                  | grid-template-columns: repeat(7,minmax(0,1fr));<br>  |
| o-grid-cols-8  |                 |                 |                 |                  | grid-template-columns: repeat(8,minmax(0,1fr));<br>  |
| o-grid-cols-9  |                 |                 |                 |                  | grid-template-columns: repeat(9,minmax(0,1fr));<br>  |
| o-grid-cols-10 |                 |                 |                 |                  | grid-template-columns: repeat(10,minmax(0,1fr));<br> |
| o-grid-cols-11 |                 |                 |                 |                  | grid-template-columns: repeat(11,minmax(0,1fr));<br> |
| o-grid-cols-12 |                 |                 |                 |                  | grid-template-columns: repeat(12,minmax(0,1fr));<br> |

## Column presets
| Class           | Properties                                          |
|-----------------|-----------------------------------------------------|
| o-grid-cols-1-2 | grid-template-columns: minmax(0,1fr) minmax(0,2fr);<br> |
| o-grid-cols-1-3 | grid-template-columns: minmax(0,1fr) minmax(0,3fr);<br> |
| o-grid-cols-1-5 | grid-template-columns: minmax(0,1fr) minmax(0,5fr);<br> |
| o-grid-cols-2-1 | grid-template-columns: minmax(0,2fr) minmax(0,1fr);<br> |
| o-grid-cols-2-3 | grid-template-columns: minmax(0,2fr) minmax(0,3fr);<br> |
| o-grid-cols-3-1 | grid-template-columns: minmax(0,3fr) minmax(0,1fr);<br> |
| o-grid-cols-3-2 | grid-template-columns: minmax(0,3fr) minmax(0,2fr);<br> |
| o-grid-cols-5-1 | grid-template-columns: minmax(0,5fr) minmax(0,1fr);<br> |

## Column span
| Extra small     | Large             | Medium            | Small             | Extra small        | Properties                      |
|-----------------|-------------------|-------------------|-------------------|--------------------|---------------------------------|
| o-col-auto      | o-col-auto-l      | o-col-auto-m      | o-col-auto-s      | o-col-auto-xs      | grid-column: auto;<br>              |
| o-col-span-1    | o-col-span-l-1    | o-col-span-m-1    | o-col-span-s-1    | o-col-span-xs-1    | grid-column: span 1 / span 1;<br>   |
| o-col-span-2    | o-col-span-l-2    | o-col-span-m-2    | o-col-span-s-2    | o-col-span-xs-2    | grid-column: span 2 / span 2;<br>   |
| o-col-span-3    | o-col-span-l-3    | o-col-span-m-3    | o-col-span-s-3    | o-col-span-xs-3    | grid-column: span 3 / span 3;<br>   |
| o-col-span-4    | o-col-span-l-4    | o-col-span-m-4    | o-col-span-s-4    | o-col-span-xs-4    | grid-column: span 4 / span 4;<br>   |
| o-col-span-5    | o-col-span-l-5    | o-col-span-m-5    | o-col-span-s-5    | o-col-span-xs-5    | grid-column: span 5 / span 5;<br>   |
| o-col-span-6    | o-col-span-l-6    | o-col-span-m-6    | o-col-span-s-6    | o-col-span-xs-6    | grid-column: span 6 / span 6;<br>   |
| o-col-span-7    | o-col-span-l-7    | o-col-span-m-7    | o-col-span-s-7    | o-col-span-xs-7    | grid-column: span 7 / span 7;<br>   |
| o-col-span-8    | o-col-span-l-8    | o-col-span-m-8    | o-col-span-s-8    | o-col-span-xs-8    | grid-column: span 8 / span 8;<br>   |
| o-col-span-9    | o-col-span-l-9    | o-col-span-m-9    | o-col-span-s-9    | o-col-span-xs-9    | grid-column: span 9 / span 9;<br>   |
| o-col-span-10   | o-col-span-l-10   | o-col-span-m-10   | o-col-span-s-10   | o-col-span-xs-10   | grid-column: span 10 / span 10;<br> |
| o-col-span-11   | o-col-span-l-11   | o-col-span-m-11   | o-col-span-s-11   | o-col-span-xs-11   | grid-column: span 11 / span 11;<br> |
| o-col-span-12   | o-col-span-l-12   | o-col-span-m-12   | o-col-span-s-12   | o-col-span-xs-12   | grid-column: span 12 / span 12;<br> |
| o-col-span-full | o-col-span-l-full | o-col-span-m-full | o-col-span-s-full | o-col-span-xs-full | grid-column: 1 / -1;<br>            |

## Column start
| Normal           | Large              | Medium             | Small              | Extra small         | Properties              |
|------------------|--------------------|--------------------|--------------------|---------------------|-------------------------|
| o-col-start-auto | o-col-start-l-auto | o-col-start-m-auto | o-col-start-s-auto | o-col-start-xs-auto | grid-column-start: auto;<br> |
| o-col-start-1    | o-col-start-l-1    | o-col-start-m-1    | o-col-start-s-1    | o-col-start-xs-1    | grid-column-start: 1;<br>    |
| o-col-start-2    | o-col-start-l-2    | o-col-start-m-2    | o-col-start-s-2    | o-col-start-xs-2    | grid-column-start: 2;<br>    |
| o-col-start-3    | o-col-start-l-3    | o-col-start-m-3    | o-col-start-s-3    | o-col-start-xs-3    | grid-column-start: 3;<br>    |
| o-col-start-4    | o-col-start-l-4    | o-col-start-m-4    | o-col-start-s-4    | o-col-start-xs-4    | grid-column-start: 4;<br>    |
| o-col-start-5    | o-col-start-l-5    | o-col-start-m-5    | o-col-start-s-5    | o-col-start-xs-5    | grid-column-start: 5;<br>    |
| o-col-start-6    | o-col-start-l-6    | o-col-start-m-6    | o-col-start-s-6    | o-col-start-xs-6    | grid-column-start: 6;<br>    |
| o-col-start-7    | o-col-start-l-7    | o-col-start-m-7    | o-col-start-s-7    | o-col-start-xs-7    | grid-column-start: 7;<br>    |
| o-col-start-8    | o-col-start-l-8    | o-col-start-m-8    | o-col-start-s-8    | o-col-start-xs-8    | grid-column-start: 8;<br>    |
| o-col-start-9    | o-col-start-l-9    | o-col-start-m-9    | o-col-start-s-9    | o-col-start-xs-9    | grid-column-start: 9;<br>    |
| o-col-start-10   | o-col-start-l-10   | o-col-start-m-10   | o-col-start-s-10   | o-col-start-xs-10   | grid-column-start: 10;<br>   |
| o-col-start-11   | o-col-start-l-11   | o-col-start-m-11   | o-col-start-s-11   | o-col-start-xs-11   | grid-column-start: 11;<br>   |
| o-col-start-12   | o-col-start-l-12   | o-col-start-m-12   | o-col-start-s-12   | o-col-start-xs-12   | grid-column-start: 12;<br>   |

## Column end
| Normal         | Large            | Medium           | Small            | Extra small       | Properties            |
|----------------|------------------|------------------|------------------|-------------------|-----------------------|
| o-col-end-auto | o-col-end-l-auto | o-col-end-m-auto | o-col-end-s-auto | o-col-end-xs-auto | grid-column-end: auto;<br> |
| o-col-end-1    | o-col-end-l-1    | o-col-end-m-1    | o-col-end-s-1    | o-col-end-xs-1    | grid-column-end: 1;<br>    |
| o-col-end-2    | o-col-end-l-2    | o-col-end-m-2    | o-col-end-s-2    | o-col-end-xs-2    | grid-column-end: 2;<br>    |
| o-col-end-3    | o-col-end-l-3    | o-col-end-m-3    | o-col-end-s-3    | o-col-end-xs-3    | grid-column-end: 3;<br>    |
| o-col-end-4    | o-col-end-l-4    | o-col-end-m-4    | o-col-end-s-4    | o-col-end-xs-4    | grid-column-end: 4;<br>    |
| o-col-end-5    | o-col-end-l-5    | o-col-end-m-5    | o-col-end-s-5    | o-col-end-xs-5    | grid-column-end: 5;<br>    |
| o-col-end-6    | o-col-end-l-6    | o-col-end-m-6    | o-col-end-s-6    | o-col-end-xs-6    | grid-column-end: 6;<br>    |
| o-col-end-7    | o-col-end-l-7    | o-col-end-m-7    | o-col-end-s-7    | o-col-end-xs-7    | grid-column-end: 7;<br>    |
| o-col-end-8    | o-col-end-l-8    | o-col-end-m-8    | o-col-end-s-8    | o-col-end-xs-8    | grid-column-end: 8;<br>    |
| o-col-end-9    | o-col-end-l-9    | o-col-end-m-9    | o-col-end-s-9    | o-col-end-xs-9    | grid-column-end: 9;<br>    |
| o-col-end-10   | o-col-end-l-10   | o-col-end-m-10   | o-col-end-s-10   | o-col-end-xs-10   | grid-column-end: 10;<br>   |
| o-col-end-11   | o-col-end-l-11   | o-col-end-m-11   | o-col-end-s-11   | o-col-end-xs-11   | grid-column-end: 11;<br>   |
| o-col-end-12   | o-col-end-l-12   | o-col-end-m-12   | o-col-end-s-12   | o-col-end-xs-12   | grid-column-end: 12;<br>   |


## Rows
| Normal           | Large              | Medium             | Small              | Extra small         | Properties                                    |
|------------------|--------------------|--------------------|--------------------|---------------------|-----------------------------------------------|
| o-grid-rows-none | o-grid-rows-l-none | o-grid-rows-m-none | o-grid-rows-s-none | o-grid-rows-xs-none | grid-template-rows: none;<br>                      |
| o-grid-rows-1    | o-grid-rows-l-1    | o-grid-rows-m-1    | o-grid-rows-s-1    | o-grid-rows-xs-1    | grid-template-rows: repeat(1, minmax(0, 1fr));<br> |
| o-grid-rows-2    | o-grid-rows-l-2    | o-grid-rows-m-2    | o-grid-rows-s-2    | o-grid-rows-xs-2    | grid-template-rows: repeat(2, minmax(0, 1fr));<br> |
| o-grid-rows-3    | o-grid-rows-l-3    | o-grid-rows-m-3    | o-grid-rows-s-3    | o-grid-rows-xs-3    | grid-template-rows: repeat(3, minmax(0, 1fr));<br> |
| o-grid-rows-4    | o-grid-rows-l-4    | o-grid-rows-m-4    | o-grid-rows-s-4    | o-grid-rows-xs-4    | grid-template-rows: repeat(4, minmax(0, 1fr));<br> |
| o-grid-rows-5    | o-grid-rows-l-5    | o-grid-rows-m-5    | o-grid-rows-s-5    | o-grid-rows-xs-5    | grid-template-rows: repeat(5, minmax(0, 1fr));<br> |
| o-grid-rows-6    | o-grid-rows-l-6    | o-grid-rows-m-6    | o-grid-rows-s-6    | o-grid-rows-xs-6    | grid-template-rows: repeat(6, minmax(0, 1fr));<br> |

## Row span
| Normal          | Large             | Medium            | Small             | Extra small        | Properties                |
|-----------------|-------------------|-------------------|-------------------|--------------------|---------------------------|
| o-row-auto      | o-row-l-auto      | o-row-m-auto      | o-row-s-auto      | o-row-xs-auto      | grid-row: auto;<br>            |
| o-row-span-1    | o-row-span-l-1    | o-row-span-m-1    | o-row-span-s-1    | o-row-span-xs-1    | grid-row: span 1 / span 1;<br> |
| o-row-span-2    | o-row-span-l-2    | o-row-span-m-2    | o-row-span-s-2    | o-row-span-xs-2    | grid-row: span 2 / span 2;<br> |
| o-row-span-3    | o-row-span-l-3    | o-row-span-m-3    | o-row-span-s-3    | o-row-span-xs-3    | grid-row: span 3 / span 3;<br> |
| o-row-span-4    | o-row-span-l-4    | o-row-span-m-4    | o-row-span-s-4    | o-row-span-xs-4    | grid-row: span 4 / span 4;<br> |
| o-row-span-5    | o-row-span-l-5    | o-row-span-m-5    | o-row-span-s-5    | o-row-span-xs-5    | grid-row: span 5 / span 5;<br> |
| o-row-span-6    | o-row-span-l-6    | o-row-span-m-6    | o-row-span-s-6    | o-row-span-xs-6    | grid-row: span 6 / span 6;<br> |
| o-row-span-full | o-row-span-l-full | o-row-span-m-full | o-row-span-s-full | o-row-span-xs-full | grid-row: 1 / -1;<br>          |

## Row start
| Normal           | Large              | Medium             | Small              | Extra small         | Properties           |
|------------------|--------------------|--------------------|--------------------|---------------------|----------------------|
| o-row-start-auto | o-row-start-l-auto | o-row-start-m-auto | o-row-start-s-auto | o-row-start-xs-auto | grid-row-start: auto;<br> |
| o-row-start-1    | o-row-start-l-1    | o-row-start-m-1    | o-row-start-s-1    | o-row-start-xs-1    | grid-row-start: 1;<br>    |
| o-row-start-2    | o-row-start-l-2    | o-row-start-m-2    | o-row-start-s-2    | o-row-start-xs-2    | grid-row-start: 2;<br>    |
| o-row-start-3    | o-row-start-l-3    | o-row-start-m-3    | o-row-start-s-3    | o-row-start-xs-3    | grid-row-start: 3;<br>    |
| o-row-start-4    | o-row-start-l-4    | o-row-start-m-4    | o-row-start-s-4    | o-row-start-xs-4    | grid-row-start: 4;<br>    |
| o-row-start-5    | o-row-start-l-5    | o-row-start-m-5    | o-row-start-s-5    | o-row-start-xs-5    | grid-row-start: 5;<br>    |
| o-row-start-6    | o-row-start-l-6    | o-row-start-m-6    | o-row-start-s-6    | o-row-start-xs-6    | grid-row-start: 6;<br>    |

## Row end
| Normal         | Large            | Medium           | Small            | Extra small       | Properties         |
|----------------|------------------|------------------|------------------|-------------------|--------------------|
| o-row-end-auto | o-row-end-l-auto | o-row-end-m-auto | o-row-end-s-auto | o-row-end-xs-auto | grid-row-end: auto;<br> |
| o-row-end-1    | o-row-end-l-1    | o-row-end-m-1    | o-row-end-s-1    | o-row-end-xs-1    | grid-row-end: 1;<br>    |
| o-row-end-2    | o-row-end-l-2    | o-row-end-m-2    | o-row-end-s-2    | o-row-end-xs-2    | grid-row-end: 2;<br>    |
| o-row-end-3    | o-row-end-l-3    | o-row-end-m-3    | o-row-end-s-3    | o-row-end-xs-3    | grid-row-end: 3;<br>    |
| o-row-end-4    | o-row-end-l-4    | o-row-end-m-4    | o-row-end-s-4    | o-row-end-xs-4    | grid-row-end: 4;<br>    |
| o-row-end-5    | o-row-end-l-5    | o-row-end-m-5    | o-row-end-s-5    | o-row-end-xs-5    | grid-row-end: 5;<br>    |
| o-row-end-6    | o-row-end-l-6    | o-row-end-m-6    | o-row-end-s-6    | o-row-end-xs-6    | grid-row-end: 6;<br>    |

---

# Gap
| Class   | Properties  |
|---------|-------------|
| o-gap-1 | gap: 0.5rem;<br> |
| o-gap-2 | gap: 1rem;<br>   |
| o-gap-3 | gap: 1.5rem;<br> |
| o-gap-4 | gap: 2.5rem;<br> |
| o-gap-5 | gap: 3rem;<br>   |
| o-gap-6 | gap: 4.5rem;<br> |

---

# Text
## Font size
| Class   | Properties                                                                    |
|---------|-------------------------------------------------------------------------------|
| o-t-xs  | font-size: 0.75rem;<br> line-height: 1rem;<br>                                          |
| o-t-s   | font-size: 0.875rem;<br> line-height: 1.25rem;<br>                                      |
| o-t-m   | font-size: 1rem;<br> line-height: 1.5rem;<br>                                           |
| o-t-l   | font-size: clamp(1.15rem,1.8vw,1.3rem);<br>line-height: clamp(1.6rem,2.2vw,2.1rem);<br> |
| o-t-xl  | font-size: clamp(1.31rem,2vw,1.625rem);<br>line-height: clamp(1.9rem,2vw,2.6rem);<br>   |
| o-t-2xl | font-size: clamp(1.5rem,2.4vw,1.95rem);<br>line-height: clamp(2.3rem,2.4vw,2.9rem);<br> |
| o-t-3xl | font-size: clamp(1.8rem,3.4vw,2.4rem);<br>line-height: clamp(2.5rem,3.4vw,3.5rem);<br>  |
| o-t-4xl | font-size: clamp(2.25rem,4.4vw,3.1rem);<br>line-height: clamp(3.1rem,4.4vw,4.2rem);<br> |
| o-t-5xl | font-size: clamp(3rem,5.4vw,4rem);<br>line-height: clamp(3.5rem,5.4vw,5.1rem);<br>      |

## Colors
| Class      | Properties     |
|------------|----------------|
| o-t-light  | color: #ffffff;<br> |
| o-t-dark   | color: #11151B;<br> |
| o-t-accent | color: #02DCD6;<br> |
> These colours can be changed in the Oxygen editor

## Headings
| Class  | Properties                                                                                    |
|--------|-----------------------------------------------------------------------------------------------|
| o-h1   | font-size: clamp(3rem,5.4vw,4rem);<br>line-height: clamp(3rem,5.4vw,4rem);<br>font-weight: 600;<br>          |
| o-h1-b | font-size: clamp(3.4rem,6vw,4.8rem);<br>line-height: clamp(3.75rem,6vw,4.8rem);<br>font-weight: 700;<br>     |
| o-h2   | font-size: clamp(2.25rem,4.4vw,3rem);<br>line-height: clamp(2.25rem,4.4vw,3.6rem);<br>font-weight: 600;<br>  |
| o-h3   | font-size: clamp(1.8rem,3.4vw,2.4rem);<br>line-height: clamp(2.15rem,3.4vw,2.9rem);<br>font-weight: 600;<br> |
| o-h4   | font-size: clamp(1.25rem,2.5vw,1.7rem);<br>line-height: clamp(1.5rem,2.5vw,2.4rem);<br>font-weight: 600;<br> |
| o-h5   | font-size: clamp(1rem,1.2vw,1.25rem);<br>line-height: clamp(1.6rem,1.2vw,2.8rem);<br>font-weight: 600;<br>   |
| o-h6   | -                                                                                             |

## Font weight
| Class          | Properties       |
|----------------|------------------|
| o-f-thin       | font-weight: 100;<br> |
| o-f-extralight | font-weight: 200;<br> |
| o-f-light      | font-weight: 300;<br> |
| o-f-normal     | font-weight: 400;<br> |
| o-f-medium     | font-weight: 500;<br> |
| o-f-semibold   | font-weight: 600;<br> |
| o-f-bold       | font-weight: 700;<br> |
| o-f-extrabold  | font-weight: 800;<br> |
| o-f-black      | font-weight: 900;<br> |

## Align
| Normal      | Large         | Medium      | Small       | Extra small  | Properties          |
|-------------|---------------|-------------|-------------|--------------|---------------------|
| o-t-left    | o-t-left-l    | o-t-left-m  | o-left-s    | o-left-xs    | text-align: left;<br>    |
| o-t-center  | o-t-center-l  | o-center-m  | o-center-s  | o-center-xs  | text-align: center;<br>  |
| o-t-right   | o-t-right-l   | o-right-m   | o-right-s   | o-right-xs   | text-align: right;<br>   |
| o-t-justify | o-t-justify-l | o-justify-m | o-justify-s | o-justify-xs | text-align: justify;<br> |

## Font style
| Class        | Properties         |
|--------------|--------------------|
| o-italic     | font-style: italic;<br> |
| o-not-italic | font-style: normal;<br> |

## Transform
| Class        | Properties                 |
|--------------|----------------------------|
| o-uppercase  | text-transform: uppercase;<br>  |
| o-lowercase  | text-transform: lowercase;<br>  |
| o-capitalize | text-transform: capitalize;<br> |

## Decoration
| Class          | Properties                    |
|----------------|-------------------------------|
| o-underline    | text-decoration: underline;<br>   |
| o-line-through | text-decoration: line-through;<br> |
| o-no-underline | text-decoration: none;<br>         |

---

# Alignment
## Self
| Class           | Properties                           |
|-----------------|--------------------------------------|
| o-self-top      | margin-bottom: auto;<br>                  |
| o-self-bottom   | margin-top: auto;<br>                     |
| o-self-left     | margin-right: auto;<br>                   |
| o-self-right    | margin-left: auto;<br>                    |
| o-self-center-x | margin-left: auto;<br> margin-right: auto;<br> |
| o-self-center-y | margin-top: auto;<br> margin-bottom: auto;<br> |

## Basic
| Class    | Properties                                                                  |
|----------|-----------------------------------------------------------------------------|
| o-center | display: flex;<br>flex-direction: initial;<br>align-items: center;<br>text-align: center;<br>   |
| o-left   | display: flex;<br>flex-direction: initial;<br>align-items: flex-start;<br>text-align: left;<br> |
| o-right  | display: flex;<br>flex-direction: initial;<br>align-items: flex-end;<br>text-align: right;<br>  |

## Top
| Class        | Properties                                                                                             |
|--------------|--------------------------------------------------------------------------------------------------------|
| o-top-center | display: flex;<br>flex-direction: initial;<br>align-items: flex-start;<br>justify-content: center;<br>text-align: center;<br>   |
| o-top-left   | display: flex;<br>flex-direction: initial;<br>align-items: flex-start;<br>justify-content: flex-start;<br>text-align: left;<br> |
| o-top-right  | display: flex;<br>flex-direction: initial;<br>align-items: flex-start;<br>justify-content: flex-end;<br>text-align: right;<br>  |

## Middle
| Class           | Properties                                                                                         |
|-----------------|----------------------------------------------------------------------------------------------------|
| o-middle-center | display: flex;<br>flex-direction: initial;<br>align-items: center;<br>justify-content: center;<br>text-align: center;<br>   |
| o-middle-left   | display: flex;<br>flex-direction: initial;<br>align-items: center;<br>justify-content: flex-start;<br>text-align: left;<br> |
| o-middle-right  | display: flex;<br>flex-direction: initial;<br>align-items: center;<br>justify-content: flex-end;<br>text-align: right;<br>  |

## Bottom
| Class           | Properties                                                                                           |
|-----------------|------------------------------------------------------------------------------------------------------|
| o-bottom-center | display: flex;<br>flex-direction: initial;<br>align-items: flex-end;<br>justify-content: center;<br>text-align: center;<br>   |
| o-bottom-left   | display: flex;<br>flex-direction: initial;<br>align-items: flex-end;<br>justify-content: flex-start;<br>text-align: left;<br> |
| o-bottom-right  | display: flex;<br>flex-direction: initial;<br>align-items: flex-end;<br>justify-content: flex-end;<br>text-align: right;<br>  |

---

# Position
| Class      | Properties         |
|------------|--------------------|
| o-relative | position: relative;<br> |
| o-absolute | position: absolute;<br> |
| o-fixed    | position: fixed;<br>    |
| o-sticky   | position: sticky;<br>   |


## Absolute positioning
## Top
| Class   | Properties   |
|---------|--------------|
| o-top-0 | top: 0px;<br>     |
| o-top-1 | top: 0.25rem;<br> |
| o-top-2 | top: 0.5rem;<br>  |
| o-top-3 | top: 0.75rem;<br> |
| o-top-4 | top: 1rem;<br>    |
| o-top-5 | top: 1.5rem;<br>  |
| o-top-6 | top: 2rem;<br>    |
| o-top-7 | top: 2.5rem;<br>  |
| o-top-8 | top: 4rem;<br>    |

## Right
| Class     | Properties     |
|-----------|----------------|
| o-right-0 | right: 0px;<br>     |
| o-right-1 | right: 0.25rem;<br> |
| o-right-2 | right: 0.5rem;<br>  |
| o-right-3 | right: 0.75rem;<br> |
| o-right-4 | right: 1rem;<br>    |
| o-right-5 | right: 1.5rem;<br>  |
| o-right-6 | right: 2rem;<br>    |
| o-right-7 | right: 2.5rem;<br>  |
| o-right-8 | right: 4rem;<br>    |

## Bottom
| Class      | Properties      |
|------------|-----------------|
| o-bottom-0 | bottom: 0px;<br>     |
| o-bottom-1 | bottom: 0.25rem;<br> |
| o-bottom-2 | bottom: 0.5rem;<br>  |
| o-bottom-3 | bottom: 0.75rem;<br> |
| o-bottom-4 | bottom: 1rem;<br>    |
| o-bottom-5 | bottom: 1.5rem;<br>  |
| o-bottom-6 | bottom: 2rem;<br>    |
| o-bottom-7 | bottom: 2.5rem;<br>  |
| o-bottom-8 | bottom: 4rem;<br>    |

## Left
| Class    | Properties    |
|----------|---------------|
| o-left-0 | left: 0px;<br>     |
| o-left-1 | left: 0.25rem;<br> |
| o-left-2 | left: 0.5rem;<br>  |
| o-left-3 | left: 0.75rem;<br> |
| o-left-4 | left: 1rem;<br>    |
| o-left-5 | left: 1.5rem;<br>  |
| o-left-6 | left: 2rem;<br>    |
| o-left-7 | left: 2.5rem;<br>  |
| o-left-8 | left: 4rem;<br>    |

## Center x-axis
| Class      | Properties                                                                                      |
|------------|-------------------------------------------------------------------------------------------------|
| o-center-x | position: absolute;<br>left: 50%;<br>transform: translate(-50%,0);<br>-webkit-transform: translate(-50%,0);<br> |

## Center y-axis
| Class      | Properties                                                                                                     |
|------------|----------------------------------------------------------------------------------------------------------------|
| o-center-y | position: absolute;<br>left: 50%;<br>top: 50%;<br>transform: translate(-50%,-50%);<br>-webkit-transform: translate(-50%,-50%);<br> |

## Center xy
| Class         | Properties                                                                                                     |
|---------------|----------------------------------------------------------------------------------------------------------------|
| o-center-auto | position: absolute;<br>left: 50%;<br>top: 50%;<br>transform: translate(-50%,-50%);<br>-webkit-transform: translate(-50%,-50%);<br> |

---

# Margin
## All sides
| Class | Properties                             |
|-------|----------------------------------------|
| o-m-0 | margin: 0px;<br>                            |
| o-m-1 | margin: clamp(0.25rem,1vmin,0.5rem);<br>    |
| o-m-2 | margin: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-m-3 | margin: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-m-4 | margin: clamp(1rem,5vmin,2.75rem);<br>      |
| o-m-5 | margin: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-m-6 | margin: clamp(2rem,7vmin,5rem);<br>         |
| o-m-7 | margin: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-m-8 | margin: clamp(3.25rem,12vmin,8.125rem);<br> |

## Margin top
| Class  | Properties                                  |
|--------|---------------------------------------------|
| o-mt-0 | margin-top: 0px;<br>                             |
| o-mt-1 | margin-top: clamp(0.5rem,1vmin,0.5rem);<br>      |
| o-mt-2 | margin-top: clamp(1.25rem,2vmin,1.25rem);<br>    |
| o-mt-3 | margin-top: clamp(2rem,3.5vmin,2rem);<br>        |
| o-mt-4 | margin-top: clamp(2.75rem,5vmin,2.75rem);<br>    |
| o-mt-5 | margin-top: clamp(4rem,6.25vmin,4rem);<br>       |
| o-mt-6 | margin-top: clamp(5rem,7vmin,5rem);<br>          |
| o-mt-7 | margin-top: clamp(6.5rem,9.5vmin,6.5rem);<br>    |
| o-mt-8 | margin-top: clamp(8.125rem,12vmin,8.125rem);<br> |

## Margin right
| Class  | Properties                                   |
|--------|----------------------------------------------|
| o-mr-0 | margin-right: 0px;<br>                            |
| o-mr-1 | margin-right: clamp(0.25rem,1vmin,0.5rem);<br>    |
| o-mr-2 | margin-right: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-mr-3 | margin-right: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-mr-4 | margin-right: clamp(1rem,5vmin,2.75rem);<br>      |
| o-mr-5 | margin-right: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-mr-6 | margin-right: clamp(2rem,7vmin,5rem);<br>         |
| o-mr-7 | margin-right: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-mr-8 | margin-right: clamp(3.25rem,12vmin,8.125rem);<br> |

## Margin bottom
| Class  | Properties                                     |
|--------|------------------------------------------------|
| o-mb-0 | margin-bottom: 0px;<br>                             |
| o-mb-1 | margin-bottom: clamp(0.5rem,1vmin,0.5rem);<br>      |
| o-mb-2 | margin-bottom: clamp(1.25rem,2vmin,1.25rem);<br>    |
| o-mb-3 | margin-bottom: clamp(2rem,3.5vmin,2rem);<br>        |
| o-mb-4 | margin-bottom: clamp(2.75rem,5vmin,2.75rem);<br>    |
| o-mb-5 | margin-bottom: clamp(4rem,6.25vmin,4rem);<br>       |
| o-mb-6 | margin-bottom: clamp(5rem,7vmin,5rem);<br>          |
| o-mb-7 | margin-bottom: clamp(6.5rem,9.5vmin,6.5rem);<br>    |
| o-mb-8 | margin-bottom: clamp(8.125rem,12vmin,8.125rem);<br> |

## Margin left
| Class  | Properties                                  |
|--------|---------------------------------------------|
| o-ml-0 | margin-left: 0px;<br>                            |
| o-ml-1 | margin-left: clamp(0.25rem,1vmin,0.5rem);<br>    |
| o-ml-2 | margin-left: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-ml-3 | margin-left: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-ml-4 | margin-left: clamp(1rem,5vmin,2.75rem);<br>      |
| o-ml-5 | margin-left: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-ml-6 | margin-left: clamp(2rem,7vmin,5rem);<br>         |
| o-ml-7 | margin-left: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-ml-8 | margin-left: clamp(3.25rem,12vmin,8.125rem);<br> |

## Margin left-right
| Class  | Properties                                                                              |
|--------|-----------------------------------------------------------------------------------------|
| o-mx-0 | margin-left: 0px;<br>margin-right: 0px;<br>                                                       |
| o-mx-1 | margin-left: clamp(0.25rem,1vmin,0.5rem);<br>margin-right: clamp(0.25rem,1vmin,0.5rem);<br>       |
| o-mx-2 | margin-left: clamp(0.5rem,2vmin,1.25rem);<br>margin-right: clamp(0.5rem,2vmin,1.25rem);<br>       |
| o-mx-3 | margin-left: clamp(0.75rem,3.5vmin,2rem);<br>margin-right: clamp(0.75rem,3.5vmin,2rem);<br>       |
| o-mx-4 | margin-left: clamp(1rem,5vmin,2.75rem);<br>margin-right: clamp(1rem,5vmin,2.75rem);<br>           |
| o-mx-5 | margin-left: clamp(1.25rem,6.25vmin,4rem);<br>margin-right: clamp(1.25rem,6.25vmin,4rem);<br>     |
| o-mx-6 | margin-left: clamp(2rem,7vmin,5rem);<br>margin-right: clamp(2rem,7vmin,5rem);<br>                 |
| o-mx-7 | margin-left: clamp(2.75rem,9.5vmin,6.5rem);<br>margin-right: clamp(2.75rem,9.5vmin,6.5rem);<br>   |
| o-mx-8 | margin-left: clamp(3.25rem,12vmin,8.125rem);<br>margin-right: clamp(3.25rem,12vmin,8.125rem);<br> |

## Margin top-bottom
| Class  | Properties                                                                                |
|--------|-------------------------------------------------------------------------------------------|
| o-my-0 | margin-top: 0px;<br>margin-bottom: 0px;<br>                                                         |
| o-my-1 | margin-top: clamp(0.25rem,1vmin,0.5rem);<br>margin-bottom: clamp(0.25rem,1vmin,0.5rem);<br>         |
| o-my-2 | margin-top: clamp(1.25rem,2vmin,1.25rem);<br>margin-bottom: clamp(1.25rem,2vmin,1.25rem);<br>       |
| o-my-3 | margin-top: clamp(2rem,3.5vmin,2rem);<br>margin-bottom: clamp(2rem,3.5vmin,2rem);<br>               |
| o-my-4 | margin-top: clamp(2.75rem,5vmin,2.75rem);<br>margin-bottom: clamp(2.75rem,5vmin,2.75rem);<br>       |
| o-my-5 | margin-top: clamp(4rem,6.25vmin,4rem);<br>margin-bottom: clamp(4rem,6.25vmin,4rem);<br>             |
| o-my-6 | margin-top: clamp(5rem,7vmin,5rem);<br>margin-bottom: clamp(5rem,7vmin,5rem);<br>                   |
| o-my-7 | margin-top: clamp(6.5rem,9.5vmin,6.5rem);<br>margin-bottom: clamp(6.5rem,9.5vmin,6.5rem);<br>       |
| o-my-8 | margin-top: clamp(8.125rem,12vmin,8.125rem);<br>margin-bottom: clamp(8.125rem,12vmin,8.125rem);<br> |

---

# Padding
## All sides
| Class | Properties                              |
|-------|-----------------------------------------|
| o-p-0 | padding: 0px;<br>                            |
| o-p-1 | padding: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-p-2 | padding: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-p-3 | padding: clamp(1rem,5vmin,2.75rem);<br>      |
| o-p-4 | padding: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-p-5 | padding: clamp(2rem,7vmin,5rem);<br>         |
| o-p-6 | padding: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-p-7 | padding: clamp(3.25rem,12vmin,8.125rem);<br> |
| o-p-8 | padding: clamp(4rem,15vmin,9.5rem);<br>      |

## Padding top
| Class  | Properties                                  |
|--------|---------------------------------------------|
| o-pt-0 | padding-top: 0px;<br>                            |
| o-pt-1 | padding-top: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-pt-2 | padding-top: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-pt-3 | padding-top: clamp(1rem,5vmin,2.75rem);<br>      |
| o-pt-4 | padding-top: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-pt-5 | padding-top: clamp(2rem,7vmin,5rem);<br>         |
| o-pt-6 | padding-top: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-pt-7 | padding-top: clamp(3.25rem,12vmin,8.125rem);<br> |
| o-pt-8 | padding-top: clamp(4rem,15vmin,9.5rem);<br>      |

## Padding right
| Class  | Properties                                    |
|--------|-----------------------------------------------|
| o-pr-0 | padding-right: 0px;<br>                            |
| o-pr-1 | padding-right: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-pr-2 | padding-right: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-pr-3 | padding-right: clamp(1rem,5vmin,2.75rem);<br>      |
| o-pr-4 | padding-right: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-pr-5 | padding-right: clamp(2rem,7vmin,5rem);<br>         |
| o-pr-6 | padding-right: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-pr-7 | padding-right: clamp(3.25rem,12vmin,8.125rem);<br> |
| o-pr-8 | padding-right: clamp(4rem,15vmin,9.5rem);<br>      |

## Padding bottom
| Class  | Properties                                     |
|--------|------------------------------------------------|
| o-pb-0 | padding-bottom:0px;<br>                            |
| o-pb-1 | padding-bottom:clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-pb-2 | padding-bottom:clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-pb-3 | padding-bottom:clamp(1rem,5vmin,2.75rem);<br>      |
| o-pb-4 | padding-bottom:clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-pb-5 | padding-bottom:clamp(2rem,7vmin,5rem);<br>         |
| o-pb-6 | padding-bottom:clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-pb-7 | padding-bottom:clamp(3.25rem,12vmin,8.125rem);<br> |
| o-pb-8 | padding-bottom:clamp(4rem,15vmin,9.5rem);<br>      |

## Padding left
| Class  | Properties                                   |
|--------|----------------------------------------------|
| o-pl-0 | padding-left: 0px;<br>                            |
| o-pl-1 | padding-left: clamp(0.5rem,2vmin,1.25rem);<br>    |
| o-pl-2 | padding-left: clamp(0.75rem,3.5vmin,2rem);<br>    |
| o-pl-3 | padding-left: clamp(1rem,5vmin,2.75rem);<br>      |
| o-pl-4 | padding-left: clamp(1.25rem,6.25vmin,4rem);<br>   |
| o-pl-5 | padding-left: clamp(2rem,7vmin,5rem);<br>         |
| o-pl-6 | padding-left: clamp(2.75rem,9.5vmin,6.5rem);<br>  |
| o-pl-7 | padding-left: clamp(3.25rem,12vmin,8.125rem);<br> |
| o-pl-8 | padding-left: clamp(4rem,15vmin,9.5rem);<br>      |

## Padding left-right
| Class  | Properties                                                                                |
|--------|-------------------------------------------------------------------------------------------|
| o-px-0 | padding-left: 0px;<br>padding-right: 0px;<br>                                                       |
| o-px-1 | padding-left: clamp(0.5rem,2vmin,1.25rem);<br>padding-right: clamp(0.5rem,2vmin,1.25rem);<br>       |
| o-px-2 | padding-left: clamp(0.75rem,3.5vmin,2rem);<br>padding-right: clamp(0.75rem,3.5vmin,2rem);<br>       |
| o-px-3 | padding-left: clamp(1rem,5vmin,2.75rem);<br>padding-right: clamp(1rem,5vmin,2.75rem);<br>           |
| o-px-4 | padding-left: clamp(1.25rem,6.25vmin,4rem);<br>padding-right: clamp(1.25rem,6.25vmin,4rem);<br>     |
| o-px-5 | padding-left: clamp(2rem,7vmin,5rem);<br>padding-right: clamp(2rem,7vmin,5rem);<br>                 |
| o-px-6 | padding-left: clamp(2.75rem,9.5vmin,6.5rem);<br>padding-right: clamp(2.75rem,9.5vmin,6.5rem);<br>   |
| o-px-7 | padding-left: clamp(3.25rem,12vmin,8.125rem);<br>padding-right: clamp(3.25rem,12vmin,8.125rem);<br> |
| o-px-8 | padding-left: clamp(4rem,15vmin,9.5rem);<br>padding-right: clamp(4rem,15vmin,9.5rem);<br>           |

## Padding top-bottom
| Class  | Properties                                                                                |
|--------|-------------------------------------------------------------------------------------------|
| o-py-0 | padding-top: 0px;<br>padding-bottom: 0px;<br>                                                       |
| o-py-1 | padding-top: clamp(0.5rem,2vmin,1.25rem);<br>padding-bottom: clamp(0.5rem,2vmin,1.25rem);<br>       |
| o-py-2 | padding-top: clamp(0.75rem,3.5vmin,2rem);<br>padding-bottom: clamp(0.75rem,3.5vmin,2rem);<br>       |
| o-py-3 | padding-top: clamp(1rem,5vmin,2.75rem);<br>padding-bottom: clamp(1rem,5vmin,2.75rem);<br>           |
| o-py-4 | padding-top: clamp(1.25rem,6.25vmin,4rem);<br>padding-bottom: clamp(1.25rem,6.25vmin,4rem);<br>     |
| o-py-5 | padding-top: clamp(2rem,7vmin,5rem);<br>padding-bottom: clamp(2rem,7vmin,5rem);<br>                 |
| o-py-6 | padding-top: clamp(2.75rem,9.5vmin,6.5rem);<br>padding-bottom: clamp(2.75rem,9.5vmin,6.5rem);<br>   |
| o-py-7 | padding-top: clamp(3.25rem,12vmin,8.125rem);<br>padding-bottom: clamp(3.25rem,12vmin,8.125rem);<br> |
| o-py-8 | padding-top: clamp(4rem,15vmin,9.5rem);<br>padding-bottom: clamp(4rem,15vmin,9.5rem);<br>           |

---

# Flex
## Display
| Class  | Properties    |
|--------|---------------|
| o-flex | display: flex;<br> |

## Flex direction
| Normal             | Large                | Medium               | Small                | Extra small           | Properties                     |
|--------------------|----------------------|----------------------|----------------------|-----------------------|--------------------------------|
| o-flex-row         | o-flex-l-row         | o-flex-m-row         | o-flex-s-row         | o-flex-xs-row         | flex-direction: row;<br>            |
| o-flex-row-reverse | o-flex-l-row-reverse | o-flex-m-row-reverse | o-flex-s-row-reverse | o-flex-xs-row-reverse | flex-direction: row-reverse;<br>    |
| o-flex-col         | o-flex-l-col         | o-flex-m-col         | o-flex-s-col         | o-flex-xs-col         | flex-direction: column;<br>         |
| o-flex-col-reverse | o-flex-l-col-reverse | o-flex-m-col-reverse | o-flex-s-col-reverse | o-flex-xs-col-reverse | flex-direction: column-reverse;<br> |

## Align items
| Normal           | Large              | Medium             | Small              | Extra small         | Properties              |
|------------------|--------------------|--------------------|--------------------|---------------------|-------------------------|
| o-align-start    | o-align-l-start    | o-align-m-start    | o-align-s-start    | o-align-xs-start    | align-items: flex-start;<br> |
| o-align-end      | o-align-l-end      | o-align-m-end      | o-align-s-end      | o-align-xs-end      | align-items: flex-end;<br>   |
| o-align-center   | o-align-l-center   | o-align-m-center   | o-align-s-center   | o-align-xs-center   | align-items: center;<br>     |
| o-align-baseline | o-align-l-baseline | o-align-m-baseline | o-align-s-baseline | o-align-xs-baseline | align-items: baseline;<br>   |
| o-align-stretch  | o-align-l-stretch  | o-align-m-stretch  | o-align-s-stretch  | o-align-xs-stretch  | align-items: stretch;<br>    |

## Justify content
| Normal            | Large               | Medium              | Small               | Extra small          | Properties                     |
|-------------------|---------------------|---------------------|---------------------|----------------------|--------------------------------|
| o-justify-start   | o-justify-l-start   | o-justify-m-start   | o-justify-s-start   | o-justify-xs-start   | justify-content: flex-start;<br>    |
| o-justify-end     | o-justify-l-end     | o-justify-m-end     | o-justify-s-end     | o-justify-xs-end     | justify-content: flex-end;<br>      |
| o-justify-center  | o-justify-l-center  | o-justify-m-center  | o-justify-s-center  | o-justify-xs-center  | justify-content: center;<br>        |
| o-justify-between | o-justify-l-between | o-justify-m-between | o-justify-s-between | o-justify-xs-between | justify-content: space-between;<br> |
| o-justify-around  | o-justify-l-around  | o-justify-m-around  | o-justify-s-around  | o-justify-xs-around  | justify-content: space-around;<br>  |
| o-justify-evenly  | o-justify-l-evenly  | o-justify-m-evenly  | o-justify-s-evenly  | o-justify-xs-evenly  | justify-content: space-evenly;<br>  |

---

# Opacity
| Class   | Properties    |
|---------|---------------|
| o-o-0   | opacity: 0;<br>    |
| o-o-5   | opacity: 0.05;<br> |
| o-o-10  | opacity: 0.1;<br>  |
| o-o-15  | opacity: 0.15;<br> |
| o-o-20  | opacity: 0.2;<br>  |
| o-o-25  | opacity: 0.25;<br> |
| o-o-30  | opacity: 0.30;<br> |
| o-o-35  | opacity: 0.35;<br> |
| o-o-40  | opacity: 0.40;<br> |
| o-o-45  | opacity: 0.45;<br> |
| o-o-50  | opacity: 0.50;<br> |
| o-o-55  | opacity: 0.55;<br> |
| o-o-60  | opacity: 0.60;<br> |
| o-o-65  | opacity: 0.65;<br> |
| o-o-70  | opacity: 0.70;<br> |
| o-o-75  | opacity: 0.75;<br> |
| o-o-80  | opacity: 0.80;<br> |
| o-o-85  | opacity: 0.85;<br> |
| o-o-90  | opacity: 0.90;<br> |
| o-o-95  | opacity: 0.95;<br> |
| o-o-100 | opacity: 1;<br>    |

---

# Shadow
| Class       | Properties                                                                                                                                                                                                                 |
|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| o-shadow-1  | box-shadow: 0 0 0 2px #F1F4F6;<br>                                                                                                                                                                                              |
| o-shadow-2  | box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;<br>                                                                                                                                                                     |
| o-shadow-3  | box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;<br>                                                                                                                                                                               |
| o-shadow-4  | box-shadow: rgba(0, 0, 0, 0.05) 0px 6px 24px 0px, rgba(0, 0, 0, 0.08) 0px   0px 0px 1px;<br>                                                                                                                                   |
| o-shadow-5  | box-shadow: rgba(0, 0, 0, 0.02) 0px 1px 3px 0px, rgba(27, 31, 35, 0.15)   0px 0px 0px 1px;<br>                                                                                                                                 |
| o-shadow-6  | box-shadow: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px, rgba(0, 0, 0, 0.06)   0px 0px 0px 1px;<br>                                                                                                                                  |
| o-shadow-7  | box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0,   0.3) 0px 30px 60px -30px;<br>                                                                                                                         |
| o-shadow-8  | box-shadow: rgba(0, 0, 0, 0.07) 0px 1px 2px, rgba(0, 0, 0, 0.07) 0px 2px   4px, rgba(0, 0, 0, 0.07) 0px 4px 8px, rgba(0, 0, 0, 0.07) 0px 8px 16px,   rgba(0, 0, 0, 0.07) 0px 16px 32px, rgba(0, 0, 0, 0.07) 0px 32px 64px;<br> |
| o-shadow-9  | box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px   6px;<br>                                                                                                                                            |
| o-shadow-10 | box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 20px, rgba(0, 0, 0, 0.23) 0px   6px 6px;<br>                                                                                                                                          |
| o-shadow-11 | box-shadow: rgba(0, 0, 0, 0.25) 0px 14px 28px, rgba(0, 0, 0, 0.22) 0px   10px 10px;<br>                                                                                                                                        |
| o-shadow-12 | box-shadow: rgba(0, 0, 0, 0.3) 0px 19px 38px, rgba(0, 0, 0, 0.22) 0px   15px 12px;<br>                                                                                                                                         |
| o-shadow-13 | box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15)   0px 1px 3px 1px;<br>                                                                                                                               |
| o-shadow-14 | box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px   13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;<br>                                                                                                 |
| o-shadow-15 | box-shadow: rgba(50, 50, 93, 0.25) 0px 30px 60px -12px inset, rgba(0, 0,   0, 0.3) 0px 18px 36px -18px inset;<br>                                                                                                              |
| o-shadow-16 | box-shadow: rgba(0, 0, 0, 0.07) 0px 1px 1px, rgba(0, 0, 0, 0.07) 0px 2px   2px, rgba(0, 0, 0, 0.07) 0px 4px 4px, rgba(0, 0, 0, 0.07) 0px 8px 8px,   rgba(0, 0, 0, 0.07) 0px 16px 16px;<br>                                     |

---

# Background color
| Class          | Properties                                                 |
|----------------|------------------------------------------------------------|
| o-bg-light     | background-color: #ffffff;<br>                                  |
| o-bg-light-alt | background-color: #f9f9f9;<br>                                  |
| o-bg-dark      | background-color: #11151B;<br>                                  |
| o-bg-dark-alt  | background-color: #212833;<br>                                  |
| o-bg-accent    | background-color: #02DCD6;<br>                                  |
| o-bg-gradient  | background-image: linear-gradient(90deg, #00e8cc, #0044a1);<br> |
| o-bg-white     | background-color: #ffffff;<br>                                  |
| o-bg-black     | background-color: #000000;<br>                                  |
> These colours can be changed in the Oxygen editor under Global Colours

---

# Gradients
## Palette
| Class  | Properties                                                                                                                                            |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| o-g-1  | background-image: -webkit-linear-gradient(to right, #02dcd6, #0044a1);<br> background-image: linear-gradient(to right, #02dcd6, #0044a1);<br>                   |
| o-g-2  | background-image: -webkit-linear-gradient(to right, #2C5364, #203A43, #0F2027);<br> background-image: linear-gradient(to right, #2C5364, #203A43, #0F2027);<br> |
| o-g-3  | background-image: -webkit-linear-gradient(to right, #f7797d, #FBD786, #C6FFDD);<br> background-image: linear-gradient(to right, #f7797d, #FBD786, #C6FFDD);<br> |
| o-g-4  | background-image: -webkit-linear-gradient(to right, #8a2387, #e94057, #f27121);<br> background-image: linear-gradient(to right, #8a2387, #e94057, #f27121);<br> |
| o-g-5  | background-image: -webkit-linear-gradient(to right, #a8ff78, #78ffd6);<br> background-image: linear-gradient(to right, #a8ff78, #78ffd6);<br>                   |
| o-g-6  | background-image: -webkit-linear-gradient(to right, #F37335, #FDC830);<br> background-image: linear-gradient(to right, #F37335, #FDC830);<br>                   |
| o-g-7  | background-image: -webkit-linear-gradient(to right, #6A82FB, #FC5C7D);<br> background-image: linear-gradient(to right, #6A82FB, #FC5C7D);<br>                   |
| o-g-8  | background-image: -webkit-linear-gradient(to right, #4b134f, #c94b4b);<br> background-image: linear-gradient(to right, #4b134f, #c94b4b);<br>                   |
| o-g-9  | background-image: -webkit-linear-gradient(to right, #78ffd6, #007991);<br> background-image: linear-gradient(to right, #78ffd6, #007991);<br>                   |
| o-g-10 | background-image: -webkit-linear-gradient(to right, #BDFFF3, #4AC29A);<br> background-image: linear-gradient(to right, #BDFFF3, #4AC29A);<br>                   |
| o-g-11 | background-image: -webkit-linear-gradient(to right, #EC6EAD, #3494E6);<br> background-image: linear-gradient(to right, #EC6EAD, #3494E6);<br>                   |
| o-g-12 | background-image: -webkit-linear-gradient(to right, #ff6a00, #ee0979);<br> background-image: linear-gradient(to right, #ff6a00, #ee0979);<br>                   |
| o-g-13 | background-image: -webkit-linear-gradient(to right, #243B55, #141E30);<br> background-image: linear-gradient(to right, #243B55, #141E30);<br>                   |
| o-g-14 | background-image: -webkit-linear-gradient(to right, #FFC371, #FF5F6D);<br> background-image: linear-gradient(to right, #FFC371, #FF5F6D);<br>                   |
| o-g-15 | background-image: -webkit-linear-gradient(to right, #135058, #F1F2B5);<br> background-image: linear-gradient(to right, #135058, #F1F2B5);<br>                   |
| o-g-16 | background-image: -webkit-linear-gradient(to right, #E1F5C4, #EDE574);<br> background-image: linear-gradient(to right, #E1F5C4, #EDE574);<br>                   |

## Border
| Class  | Properties                                                                                                                                                   | : before       | : before properties                 |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------------------------|
| o-gb-1 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 1px;<br> | o-gb-1: before | border-radius: inherit;<br>margin: -1px;<br> |
| o-gb-2 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 2px;<br> | o-gb-2: before | border-radius: inherit;<br>margin: -2px;<br> |
| o-gb-3 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 3px;<br> | o-gb-3: before | border-radius: inherit;<br>margin: -3px;<br> |
| o-gb-4 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 4px;<br> | o-gb-4: before | border-radius: inherit;<br>margin: -4px;<br> |
| o-gb-5 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 5px;<br> | o-gb-5: before | border-radius: inherit;<br>margin: -5px;<br> |
| o-gb-6 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 6px;<br> | o-gb-6: before | border-radius: inherit;<br>margin: -6px;<br> |
| o-gb-7 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 7px;<br> | o-gb-7: before | border-radius: inherit;<br>margin: -7px;<br> |
| o-gb-8 | box-sizing: border-box;<br>background-clip: padding-box;<br>background-color: disabled;<br>position: relative;<br>;<br>border-color: transparent;<br>border-style: solid;<br>border-width: 8px;<br> | o-gb-8: before | border-radius: inherit;<br>margin: -8px;<br> |

---

# Border
## Border color
| Class          | Properties            |
|----------------|-----------------------|
| o-b-black      | border-color: #000000;<br> |
| o-b-white      | border-color: #ffffff;<br> |
| o-b-dark       | border-color: #11151b;<br> |
| o-b-dark-alt   | border-color: #212833;<br> |
| o-b-light      | border-color: #f9fbff;<br> |
| o-b-light-alt  | border-color: #f1f4f6;<br> |
| o-b-accent     | border-color: #2c99dd;<br> |
| o-b-accent-alt | border-color: #ffab40;<br> |
> These colours can be changed in the Oxygen editor under Global Colours

## Border radius
| Class    | Properties                              |
|----------|-----------------------------------------|
| o-r-1    | border-radius: 0.25rem;<br> overflow: hidden;<br> |
| o-r-2    | border-radius: 0.5rem;<br> overflow: hidden;<br>  |
| o-r-3    | border-radius: 0.75rem;<br> overflow: hidden;<br> |
| o-r-4    | border-radius: 1rem;<br> overflow: hidden;<br>    |
| o-r-5    | border-radius: 1.5rem;<br> overflow: hidden;<br>  |
| o-r-6    | border-radius: 2rem;<br> overflow: hidden;<br>    |
| o-r-7    | border-radius: 3rem;<br> overflow: hidden;<br>    |
| o-r-8    | border-radius: 4rem;<br> overflow: hidden;<br>    |
| o-r-full | border-radius: 99999px;<br> overflow: hidden;<br> |

## All sides size
| Class | Properties                           |
|-------|--------------------------------------|
| o-b-1 | border-style: solid;<br>border-width: 1px;<br> |
| o-b-2 | border-style: solid;<br>border-width: 2px;<br> |
| o-b-3 | border-style: solid;<br>border-width: 3px;<br> |
| o-b-4 | border-style: solid;<br>border-width: 4px;<br> |
| o-b-5 | border-style: solid;<br>border-width: 5px;<br> |
| o-b-6 | border-style: solid;<br>border-width: 6px;<br> |
| o-b-7 | border-style: solid;<br>border-width: 7px;<br> |
| o-b-8 | border-style: solid;<br>border-width: 8px;<br> |

## Top size
| Class  | Properties                               |
|--------|------------------------------------------|
| o-bt-1 | border-top-style: solid;<br>border-width: 1px;<br> |
| o-bt-2 | border-top-style: solid;<br>border-width: 2px;<br> |
| o-bt-3 | border-top-style: solid;<br>border-width: 3px;<br> |
| o-bt-4 | border-top-style: solid;<br>border-width: 4px;<br> |
| o-bt-5 | border-top-style: solid;<br>border-width: 5px;<br> |
| o-bt-6 | border-top-style: solid;<br>border-width: 6px;<br> |
| o-bt-7 | border-top-style: solid;<br>border-width: 7px;<br> |
| o-bt-8 | border-top-style: solid;<br>border-width: 8px;<br> |

## Right size
| Class  | Properties                                 |
|--------|--------------------------------------------|
| o-br-1 | border-right-style: solid;<br>border-width: 1px;<br> |
| o-br-2 | border-right-style: solid;<br>border-width: 2px;<br> |
| o-br-3 | border-right-style: solid;<br>border-width: 3px;<br> |
| o-br-4 | border-right-style: solid;<br>border-width: 4px;<br> |
| o-br-5 | border-right-style: solid;<br>border-width: 5px;<br> |
| o-br-6 | border-right-style: solid;<br>border-width: 6px;<br> |
| o-br-7 | border-right-style: solid;<br>border-width: 7px;<br> |
| o-br-8 | border-right-style: solid;<br>border-width: 8px;<br> |

## Bottom size
| Class  | Properties                                  |
|--------|---------------------------------------------|
| o-bb-1 | border-bottom-style: solid;<br>border-width: 1px;<br> |
| o-bb-2 | border-bottom-style: solid;<br>border-width: 2px;<br> |
| o-bb-3 | border-bottom-style: solid;<br>border-width: 3px;<br> |
| o-bb-4 | border-bottom-style: solid;<br>border-width: 4px;<br> |
| o-bb-5 | border-bottom-style: solid;<br>border-width: 5px;<br> |
| o-bb-6 | border-bottom-style: solid;<br>border-width: 6px;<br> |
| o-bb-7 | border-bottom-style: solid;<br>border-width: 7px;<br> |
| o-bb-8 | border-bottom-style: solid;<br>border-width: 8px;<br> |

## Left size
| Class  | Properties                                |
|--------|-------------------------------------------|
| o-bl-1 | border-left-style: solid;<br>border-width: 1px;<br> |
| o-bl-2 | border-left-style: solid;<br>border-width: 2px;<br> |
| o-bl-3 | border-left-style: solid;<br>border-width: 3px;<br> |
| o-bl-4 | border-left-style: solid;<br>border-width: 4px;<br> |
| o-bl-5 | border-left-style: solid;<br>border-width: 5px;<br> |
| o-bl-6 | border-left-style: solid;<br>border-width: 6px;<br> |
| o-bl-7 | border-left-style: solid;<br>border-width: 7px;<br> |
| o-bl-8 | border-left-style: solid;<br>border-width: 8px;<br> |

---

# Components
## Buttons
| Class            | Properties                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| o-btn-s          | font-weight: 500;<br>font-size: 1rem;<br>padding-left: 1rem;<br>padding-right: 1rem;<br>padding-bottom: 0.5rem;<br>padding-top: 0.5rem;<br>transition-duration: 0.2s;<br>line-height: 1;<br>text-align: center;<br>border-radius: 0.5rem;<br>                                                                                                                                                                                                                                                                                                              |
| o-btn-m          | font-weight: 500;<br>font-size: 1.125rem;<br>padding-left: 1.5rem;<br>padding-right: 1.5rem;<br>padding-bottom: 0.5rem;<br>padding-top: 0.5rem;<br>transition-duration: 0.2s;<br>text-align: center;<br>border-radius: 0.5rem;<br>                                                                                                                                                                                                                                                                                                                    |
| o-btn-l          | font-weight: 600;<br>font-size: 1.25rem;<br>padding-left: 1.5rem;<br>padding-right: 1.5rem;<br>padding-bottom: 1rem;<br>padding-top: 1rem;<br>transition-duration: 0.2s;<br>line-height: 1;<br>text-align: center;<br>border-radius: 0.5rem;<br>                                                                                                                                                                                                                                                                                                           |
| o-btn-xl         | font-weight: 700;<br>font-size: 1.7rem;<br>padding-left: 1.5rem;<br>padding-right: 1.5rem;<br>transition-duration: 0.2s;<br>line-height: 1;<br>padding-top: 1rem;<br>padding-bottom: 1rem;<br>text-align: center;<br>border-radius: 0.5rem;<br>                                                                                                                                                                                                                                                                                                            |
| o-btn-rounded-s  | font-weight: 500;<br>font-size: 1rem;<br>border-radius: 99999px;<br>padding-left: 1rem;<br>padding-right: 1rem;<br>border-top-width: 2px;<br>border-right-width: 2px;<br>border-bottom-width: 2px;<br>border-left-width: 2px;<br>border-top-color: #212833;<br>border-right-color: #212833;<br>border-bottom-color: #212833;<br>border-left-color: #212833;<br>border-top-style: none;<br>border-right-style: none;<br>border-bottom-style: none;<br>border-left-style: none;<br>padding-bottom: 0.5rem;<br>padding-top: 0.5rem;<br>transition-duration: 0.2s;<br>line-height: 1;<br>text-align: center;<br>           |
| o-btn-rounded-m  | font-weight: 500;<br>font-size: 1.125rem;<br>border-radius: 99999px;<br>padding-left: 1.5rem;<br>padding-right: 1.5rem;<br>border-top-width: 2px;<br>border-right-width: 2px;<br>border-bottom-width: 2px;<br>border-left-width: 2px;<br>border-top-color: #212833;<br>border-right-color: #212833;<br>border-bottom-color: #212833;<br>border-left-color: #212833;<br>border-top-style: none;<br>border-right-style: none;<br>border-bottom-style: none;<br>border-left-style: none;<br>padding-bottom: 0.75rem;<br>padding-top: 0.75rem;<br>transition-duration: 0.2s;<br>line-height: 1;<br>text-align: center;<br> |
| o-btn-rounded-l  | font-weight: 600;<br>font-size: 1.25rem;<br>transition-duration: 0.2s;<br>border-radius: 99999px;<br>border-top-style: none;<br>border-right-style: none;<br>border-bottom-style: none;<br>border-left-style: none;<br>border-top-width: 0px;<br>border-right-width: 0px;<br>border-bottom-width: 0px;<br>border-left-width: 0px;<br>line-height: 1;<br>text-align: center;<br>padding-top: 1rem;<br>padding-bottom: 1rem;<br>padding-left: 1.5rem;<br>padding-right: 1.5rem;<br>                                                                                                                  |
| o-btn-rounded-xl | font-weight: 700;<br>font-size: 1.7rem;<br>padding-left: 1.5rem;<br>padding-right: 1.5rem;<br>transition-duration: 0.2s;<br>border-radius: 99999px;<br>border-top-style: none;<br>border-right-style: none;<br>border-bottom-style: none;<br>border-left-style: none;<br>border-top-width: 0px;<br>border-right-width: 0px;<br>border-bottom-width: 0px;<br>border-left-width: 0px;<br>line-height: 1;<br>padding-top: 1rem;<br>padding-bottom: 1rem;<br>text-align: center;<br>                                                                                                                   |