var phoneGapServices=angular.module("PhonegapServices",[]);phoneGapServices.factory("pgGeolocationFactory",["$q","$rootScope",function(n){var i=n.defer(),t={};return t.watchId=null,t.latitude="",t.getCurrentPostition=function(n){var r=function(n){i.resolve(n);t.latitude=n.coords.latitude},u=function(n){alert("code: "+n.code+"\nmessage: "+n.message+"\n");i.reject(n)};return t.watchId=navigator.geolocation.watchPosition(r,u,n),i.promise},t}]).factory("pgNotificationFactory",["$q","$rootScope",function(){var n={};return n.alert=function(n,t,i,r){navigator.notification.alert(n,r,t,i)},n.confirm=function(n,t,i,r){navigator.notification.confirm(n,t,i,r)},n}]);
/*
//# sourceMappingURL=PhonegapServices.min.js.map
*/
