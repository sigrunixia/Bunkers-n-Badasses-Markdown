---
alias: ["Stabbomancer Contagion"]
class: Assassin
cssclass: 
skilltree: Stabbomancer
slevel: 0
---
# Contagion
> `$=const slevel = dv.current().slevel; dv.span(slevel);` / 3 Skill Points

Your Elemental Damage gains `$=const slevel = dv.current().slevel; dv.span(slevel);` Splash Damage.

```dataviewjs
const {createButton} = app.plugins.plugins["buttons"];
const update = this.app.plugins.plugins["metaedit"].api.update;

// Creating Decrease button
if (dv.current().slevel === 1){
    createButton({
        app,
        el: this.container,
        args: {name: "-1 SL"}, 
        clickOverride: {click: update, params: ['slevel', 0, dv.current().file.path]}
    })
} else if (dv.current().slevel === 2){
    createButton({
        app,
        el: this.container,
        args: {name: "-1 SL"}, 
        clickOverride: {click: update, params: ['slevel', 1, dv.current().file.path]}
    })
} else if (dv.current().slevel === 3){
    createButton({
        app,
        el: this.container,
        args: {name: "-1 SL"}, 
        clickOverride: {click: update, params: ['slevel', 2, dv.current().file.path]}
    })
} else if (dv.current().slevel === 0){
    createButton({
        app,
        el: this.container,
        args: {name: "Min"}, 
        clickOverride: {
            click: function(){},
            params: []
        }
    });
}
// Creating Increase Button
if (dv.current().slevel === 0){
    createButton({
        app,
        el: this.container,
        args: {name: "Unlock Skill"}, 
        clickOverride: {click: update, params: ['slevel', 1, dv.current().file.path]}
    })
} else if (dv.current().slevel === 1){
    createButton({
        app,
        el: this.container,
        args: {name: "+1 SL"}, 
        clickOverride: {click: update, params: ['slevel', 2, dv.current().file.path]}
    })
} else if (dv.current().slevel === 2){
    createButton({
        app,
        el: this.container,
        args: {name: "+1 SL"}, 
        clickOverride: {click: update, params: ['slevel', 3, dv.current().file.path]}
    })
} else if (dv.current().slevel === 3){
    createButton({
        app,
        el: this.container,
        args: {name: "Max"}, 
        clickOverride: {
            click: function(){},
            params: []
        }
    });
}
```