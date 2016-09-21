# angular-material-design
[Angular material login form](http://codepen.io/ThomasBurleson/pen/wBgVpao)

![Image of angular material login form](http://res.cloudinary.com/dz0dtvouo/image/upload/c_fit,h_654,w_1217/v1474478940/angular-material-login_gpdt5d.png)

```html
<div ng-app="BlankApp" ng-controller="AppCtrl as appCtrl" layout="column" ng-cloak layout-align="center center" layout-fill>		
	<div layout="column" class="loginBox md-whiteframe-z1" >
		<md-toolbar>
			<h2 class="md-toolbar-tools"><span>Login</span></h2>
		</md-toolbar>
		<md-content	class="md-padding" layout="column">
			<md-input-container>
				<label>Email</label>
				<input type="email" ng-model="user.email">
			</md-input-container>
			<md-input-container>
				<label>Password</label>
				<input type="password" ng-model="user.password">
			</md-input-container>
			<div layout="row" layout-align="center center" style="padding-top:20px;">
				<md-button class="md-raised md-primary">Login</md-button>
				<div flex></div>
				<md-button href=""  md-no-ink> Forgot Password</md-button>
			</div>
		</md-content>
	</div>
</div>
```