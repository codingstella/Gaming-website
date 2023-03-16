# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link
  href="https://fonts.googleapis.com/css2?family=Oxanium:wght@400;500;600;700&family=Work+Sans:wght@600&display=swap"
  rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

---

## Colors

### Background color

``` css
--bg-purple: hsla(267, 100%, 63%, 1);
--bg-purple-alpha-30: hsla(267, 100%, 63%, 0.3);
--bg-dark-purple: hsla(279, 42%, 9%, 1);
--bg-oxford-blue: hsla(240, 63%, 13%, 1);
--bg-oxford-blue-alpha-95: hsla(240, 63%, 13%, 0.95);
--bg-oxford-blue-alpha-90: hsla(240, 63%, 13%, 0.9);
--bg-oxford-blue-alpha-80: hsla(240, 63%, 13%, 0.8);
```

### Gradient color

``` css
--gradient-1: linear-gradient(to right bottom, hsl(299, 100%, 52%), hsl(291, 100%, 58%), hsl(283, 100%, 60%), hsl(273, 100%, 62%), hsl(262, 100%, 63%), hsl(242, 100%, 69%), hsl(223, 100%, 62%), hsl(210, 100%, 50%), hsl(203, 100%, 50%), hsl(198, 100%, 50%), hsl(192, 100%, 48%), hsl(185, 90%, 48%));
--gradient-2: linear-gradient(90deg, transparent 0%, #9841ff 50%, transparent 100%);
```

### Text color

``` css
--text-white: hsla(0, 0%, 100%, 1);
--text-gainsboro: hsla(0, 0%, 87%, 1);
--text-champagne-pink: hsla(23, 61%, 86%, 1);
--text-purple: hsla(267, 100%, 63%, 1);
```

### Border color

``` css
--border-space-cadet: hsl(240, 45%, 17%);
--border-purple-alpha-30: hsla(267, 100%, 63%, 0.3);
```

## Typography

``` css
--fontFamily-oxanium: 'Oxanium', cursive;
--fontFamily-work-sans: 'Work Sans', sans-serif;

--fontSize-1: 3.6rem;
--fontSize-2: 2.4rem;
--fontSize-3: 2rem;
--fontSize-4: 1.7rem;
--fontSize-5: 1.6rem;
--fontSize-6: 1.5rem;
--fontSize-7: 1.4rem;
--fontSize-8: 1.2rem;

--weight-regular: 400;
--weight-semiBold: 600;
--weight-bold: 700;
```

## Spacing

``` css
--section-spacing: 60px;
```

## Shadow

``` css
--shadow: 0px 2px 5px 0px hsla(0, 0%, 0%, 0.2);
```

## Border Radius

``` css
--radius-circle: 50%;
--radius-5: 5px;
--radius-3: 3px;
```

## Clip path

``` css
--clip-path-1: polygon(0 0, 100% 0, 100% 0, 0 0);
--clip-path-2: polygon(0 0, 100% 0, 100% 100%, 0 100%);
--clip-path-3: polygon(0% 0%, 90% 0, 100% 30%, 100% 100%, 0 100%);
--clip-path-4: polygon(90% 0, 100% 40%, 100% 100%, 0 100%, 0 0);
--clip-path-5: polygon(100% 0, 100% 100%, 10% 100%, 0 60%, 0 0);
--clip-path-6: polygon(10% 0, 100% 0, 100% 100%, 0 100%, 0 40%);
--clip-path-7: polygon(100% 0, 100% 60%, 90% 100%, 0 100%, 0 0);
--clip-path-8: polygon(0% 0%, 70% 0, 100% 30%, 100% 100%, 0 100%);
--clip-path-9: polygon(0 0, 90% 0, 100% 100%, 0% 100%);
```

## Transition

``` css
--transition-1: 250ms ease;
--transition-2: 500ms ease;
--cubic-out: cubic-bezier(0.05, 0.83, 0.52, 0.97);
```
