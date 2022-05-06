# Components

## Command
`ng g c <component-name>` <br />

## Manual
1. Create a new file `<component-name>.component.ts`
2. `import { Component } from '@angular/core';`
3. 
```
@Component({
  selector: 'app-component-name',
  templateUrl: './component-name.component.html',
  styleUrls: ['./component-name.component.css']
})
```

Selector = name of the tag in html when called <br />
template(Url) = inline HTML / HTML file path <br />
styles/styleUrls = [inline CSS] / [CSS file path] <br />
4. 
```export class ComponentOverviewComponent {
    // content of the code
}```