### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# اختر الأزياء

## الخطوة 1
انظر إلى القفل لمعرفة الأرقام التي يعرضها، ثم استخدم الخزانة لتحديد أي قطع من الأزياء تتطابق مع تلك الأرقام. بمجرد أن تقوم بمطابقتها، استخدم كتلة ``||hoc:الرأس، الجسم، والساقين||`` لفتح القفل.

#### ~ تلميح
تأكد من ضبط الأرقام داخل الخزانة لتطابق الأرقام الموجودة على القفل، ثم قم ببرمجة مجموعة الأزياء تلك.

```ghost
    hoc._costume_activity(HeadWear_Activity.Knight_Helmet, MidWear_Activity.Knight_Top, LowerWear_Activity.Knight_Legs)
```
```template     
    \\
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume
```