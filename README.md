如果是自定义View的那种FragmentDialog，可以使用以下的方法。<br/>
    @Override<br/>
    public void onStart() {<br/>
        super.onStart();<br/>
        ViewGroup.MarginLayoutParams params = (ViewGroup.MarginLayoutParams) view.getLayoutParams();<br/>
        params.bottomMargin = DensityUtil.dip2px(15f);<br/>
        view.setLayoutParams(params);<br/>
    }<br/><br/>

# Android底部对话框BottomDialog
![](https://github.com/xiaoyanger0825/BottomDialog/raw/master/images/a.gif)
![](https://github.com/xiaoyanger0825/BottomDialog/raw/master/images/b.gif)
