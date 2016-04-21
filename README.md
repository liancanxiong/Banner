# Banner
图片轮播库

##特性
* 自定义标题栏
	* 自定义标题文本大小、颜色、背景和对齐方式
* 自定义Indicator
	* 自定义Indicator的颜色、背景、对齐方式
* 自定义图片显示的ScaleType
* 自定义图片显示时间
* 提供点击回调接口

##自定义属性一览
	<declare-styleable name="Banner">
        <attr name="loop" format="boolean" />
        <attr name="show_indicator" format="boolean" />
        <attr name="title_gravity" format="enum">
            <enum name="left" value="0" />
            <enum name="right" value="1" />
            <enum name="center" value="2" />
        </attr>
        <attr name="indicator_gravity" format="enum">
            <enum name="left" value="0" />
            <enum name="right" value="1" />
            <enum name="center" value="2" />
        </attr>
        <attr name="title_size" format="dimension" />
        <attr name="title_color" format="color" />
        <attr name="title_background" format="color" />
        <attr name="indicator_background" format="color" />
        <attr name="scaleType" format="enum">
            <enum name="matrix" value="0" />
            <enum name="fit_xy" value="1" />
            <enum name="fit_start" value="2" />
            <enum name="fit_center" value="3" />
            <enum name="fit_end" value="4" />
            <enum name="center" value="5" />
            <enum name="center_crop" value="6" />
            <enum name="center_inside" value="7" />
        </attr>
        <attr name="loop_speed" format="integer" />
        <attr name="show_title" format="boolean" />
        <attr name="indicator_selected" format="color" />
        <attr name="indicator_unselected" format="color" />
        <attr name="direction" format="enum">
            <enum name="left" value="0" />
            <enum name="right" value="1" />
        </attr>
    </declare-styleable>