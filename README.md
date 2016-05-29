# iOS Swift CheatSheet
A handful of code snippets that I find myself googling over and over again

###Table of Content
* [Animation](#animation)
  * [UIView Animation](#uiview-animation)

#### Animation
##### UIView Animation
```
UIView.animateWithDuration(1.0, delay: 1.0, options: [.Autoreverse , .Repeat], animations: { () -> Void in
          
        }, completion: { (finished: Bool) -> Void in
           
 })
```

```
UIView.transitionWithView(view, duration: 1.0, options: [.TransitionCrossDissolve], animations: { () -> Void in
         
    }, completion: { (finished: Bool) -> Void in
         
})
```
