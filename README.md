<html lang="ja"><head><style type="text/css">@charset "UTF-8";[ng\:cloak],[ng-cloak],[data-ng-cloak],[x-ng-cloak],.ng-cloak,.x-ng-cloak,.ng-hide:not(.ng-hide-animate){display:none !important;}ng\:form{display:block;}.ng-animate-shim{visibility:hidden;}.ng-anchor{position:absolute;}</style>
<script async="" src="//www.google-analytics.com/analytics.js"></script><script>window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"54c4a6ad3a","applicationID":"55516630","transactionName":"dFoPQxELW1xSER0QFkJRBFkXFxhVTwJfTBZSRhU=","queueTime":0,"applicationTime":249,"agent":""}</script>
<script>(window.NREUM||(NREUM={})).init={ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={xpid:"VQAHUV5UARAFUVRTAQcEVg==",licenseKey:"54c4a6ad3a",applicationID:"55516630"};;/*! For license information please see nr-loader-full-1.263.0.min.js.LICENSE.txt */
(()=>{var e,t,r={2983:(e,t,r)=>{"use strict";r.d(t,{D0:()=>v,gD:()=>y,Vp:()=>s,oC:()=>w,fr:()=>I,jD:()=>j,hR:()=>A,xN:()=>b,x1:()=>c,aN:()=>T,V:()=>P});var n=r(384),i=r(7864);const o={beacon:n.NT.beacon,errorBeacon:n.NT.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},a={};function s(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!a[e])throw new Error("Info for ".concat(e," was never set"));return a[e]}function c(e,t){if(!e)throw new Error("All info objects require an agent identifier!");a[e]=(0,i.a)(t,o);const r=(0,n.nY)(e);r&&(r.info=a[e])}var d=r(993);const u=e=>{if(!e||"string"!=typeof e)return!1;try{document.createDocumentFragment().querySelector(e)}catch{return!1}return!0};var l=r(2614),f=r(944);const h="[data-nr-mask]",g=()=>{const e={mask_selector:"*",block_selector:"[data-nr-block]",mask_input_options:{color:!1,date:!1,"datetime-local":!1,email:!1,month:!1,number:!1,range:!1,search:!1,tel:!1,text:!1,time:!1,url:!1,week:!1,textarea:!1,select:!1,password:!0}};return{ajax:{deny_list:void 0,block_internal:!0,enabled:!0,harvestTimeSeconds:10,autoStart:!0},distributed_tracing:{enabled:void 0,exclude_newrelic_header:void 0,cors_use_newrelic_header:void 0,cors_use_tracecontext_headers:void 0,allowed_origins:void 0},feature_flags:[],harvest:{tooManyRequestsDelay:60},jserrors:{enabled:!0,harvestTimeSeconds:10,autoStart:!0},logging:{enabled:!0,harvestTimeSeconds:10,autoStart:!0,level:d.p_.INFO},metrics:{enabled:!0,autoStart:!0},obfuscate:void 0,page_action:{enabled:!0,harvestTimeSeconds:30,autoStart:!0},page_view_event:{enabled:!0,autoStart:!0},page_view_timing:{enabled:!0,harvestTimeSeconds:30,long_task:!1,autoStart:!0},privacy:{cookies_enabled:!0},proxy:{assets:void 0,beacon:void 0},session:{expiresMs:l.wk,inactiveMs:l.BB},session_replay:{autoStart:!0,enabled:!1,harvestTimeSeconds:60,preload:!1,sampling_rate:10,error_sampling_rate:100,collect_fonts:!1,inline_images:!1,inline_stylesheet:!0,fix_stylesheets:!0,mask_all_inputs:!0,get mask_text_selector(){return e.mask_selector},set mask_text_selector(t){u(t)?e.mask_selector="".concat(t,",").concat(h):""===t||null===t?e.mask_selector=h:(0,f.R)(5,t)},get block_class(){return"nr-block"},get ignore_class(){return"nr-ignore"},get mask_text_class(){return"nr-mask"},get block_selector(){return e.block_selector},set block_selector(t){u(t)?e.block_selector+=",".concat(t):""!==t&&(0,f.R)(6,t)},get mask_input_options(){return e.mask_input_options},set mask_input_options(t){t&&"object"==typeof t?e.mask_input_options={...t,password:!0}:(0,f.R)(7,t)}},session_trace:{enabled:!0,harvestTimeSeconds:10,autoStart:!0},soft_navigations:{enabled:!0,harvestTimeSeconds:10,autoStart:!0},spa:{enabled:!0,harvestTimeSeconds:10,autoStart:!0},ssl:void 0}},p={},m="All configuration objects require an agent identifier!";function v(e){if(!e)throw new Error(m);if(!p[e])throw new Error("Configuration for ".concat(e," was never set"));return p[e]}function b(e,t){if(!e)throw new Error(m);p[e]=(0,i.a)(t,g());const r=(0,n.nY)(e);r&&(r.init=p[e])}function y(e,t){if(!e)throw new Error(m);var r=v(e);if(r){for(var n=t.split("."),i=0;i<n.length-1;i++)if("object"!=typeof(r=r[n[i]]))return;r=r[n[n.length-1]]}return r}const R={accountID:void 0,trustKey:void 0,agentID:void 0,licenseKey:void 0,applicationID:void 0,xpid:void 0},x={};function w(e){if(!e)throw new Error("All loader-config objects require an agent identifier!");if(!x[e])throw new Error("LoaderConfig for ".concat(e," was never set"));return x[e]}function T(e,t){if(!e)throw new Error("All loader-config objects require an agent identifier!");x[e]=(0,i.a)(t,R);const r=(0,n.nY)(e);r&&(r.loader_config=x[e])}const A=(0,n.dV)().o;var S=r(6154),E=r(9324);const _={buildEnv:E.F3,distMethod:E.Xs,version:E.xv,originTime:S.WN},O={customTransaction:void 0,disabled:!1,isolatedBacklog:!1,loaderType:void 0,maxBytes:3e4,onerror:void 0,origin:""+S.gm.location,ptid:void 0,releaseIds:{},appMetadata:{},session:void 0,denyList:void 0,harvestCount:0,timeKeeper:void 0},N={};function I(e){if(!e)throw new Error("All runtime objects require an agent identifier!");if(!N[e])throw new Error("Runtime for ".concat(e," was never set"));return N[e]}function P(e,t){if(!e)throw new Error("All runtime objects require an agent identifier!");N[e]={...(0,i.a)(t,O),..._};const r=(0,n.nY)(e);r&&(r.runtime=N[e])}function j(e){return function(e){try{const t=s(e);return!!t.licenseKey&&!!t.errorBeacon&&!!t.applicationID}catch(e){return!1}}(e)}},7864:(e,t,r)=>{"use strict";r.d(t,{a:()=>i});var n=r(944);function i(e,t){try{if(!e||"object"!=typeof e)return(0,n.R)(3);if(!t||"object"!=typeof t)return(0,n.R)(4);const r=Object.create(Object.getPrototypeOf(t),Object.getOwnPropertyDescriptors(t)),o=0===Object.keys(r).length?e:r;for(let a in o)if(void 0!==e[a])try{if(null===e[a]){r[a]=null;continue}Array.isArray(e[a])&&Array.isArray(t[a])?r[a]=Array.from(new Set([...e[a],...t[a]])):"object"==typeof e[a]&&"object"==typeof t[a]?r[a]=i(e[a],t[a]):r[a]=e[a]}catch(e){(0,n.R)(1,e)}return r}catch(e){(0,n.R)(2,e)}}},9324:(e,t,r)=>{"use strict";r.d(t,{F3:()=>i,Xs:()=>o,Yq:()=>a,xv:()=>n});const n="1.263.0",i="PROD",o="CDN",a="2.0.0-alpha.12"},6154:(e,t,r)=>{"use strict";r.d(t,{OF:()=>d,RI:()=>i,Vr:()=>h,WN:()=>g,bv:()=>o,gm:()=>a,lR:()=>l,lT:()=>f,m:()=>c,mw:()=>s,sb:()=>u});var n=r(1863);const i="undefined"!=typeof window&&!!window.document,o="undefined"!=typeof WorkerGlobalScope&&("undefined"!=typeof self&&self instanceof WorkerGlobalScope&&self.navigator instanceof WorkerNavigator||"undefined"!=typeof globalThis&&globalThis instanceof WorkerGlobalScope&&globalThis.navigator instanceof WorkerNavigator),a=i?window:"undefined"!=typeof WorkerGlobalScope&&("undefined"!=typeof self&&self instanceof WorkerGlobalScope&&self||"undefined"!=typeof globalThis&&globalThis instanceof WorkerGlobalScope&&globalThis),s=Boolean("hidden"===a?.document?.visibilityState),c=""+a?.location,d=/iPad|iPhone|iPod/.test(a.navigator?.userAgent),u=d&&"undefined"==typeof SharedWorker,l=(()=>{const e=a.navigator?.userAgent?.match(/Firefox[/\s](\d+\.\d+)/);return Array.isArray(e)&&e.length>=2?+e[1]:0})(),f=Boolean(i&&window.document.documentMode),h=!!a.navigator?.sendBeacon,g=Date.now()-(0,n.t)()},4777:(e,t,r)=>{"use strict";r.d(t,{J:()=>o});var n=r(944);const i={agentIdentifier:"",ee:void 0};class o{constructor(e){try{if("object"!=typeof e)return(0,n.R)(8);this.sharedContext={},Object.assign(this.sharedContext,i),Object.entries(e).forEach((e=>{let[t,r]=e;Object.keys(i).includes(t)&&(this.sharedContext[t]=r)}))}catch(e){(0,n.R)(9,e)}}}},7295:(e,t,r)=>{"use strict";r.d(t,{Xv:()=>a,gX:()=>i,iW:()=>o});var n=[];function i(e){if(!e||o(e))return!1;if(0===n.length)return!0;for(var t=0;t<n.length;t++){var r=n[t];if("*"===r.hostname)return!1;if(s(r.hostname,e.hostname)&&c(r.pathname,e.pathname))return!1}return!0}function o(e){return void 0===e.hostname}function a(e){if(n=[],e&&e.length)for(var t=0;t<e.length;t++){let r=e[t];if(!r)continue;0===r.indexOf("http://")?r=r.substring(7):0===r.indexOf("https://")&&(r=r.substring(8));const i=r.indexOf("/");let o,a;i>0?(o=r.substring(0,i),a=r.substring(i)):(o=r,a="");let[s]=o.split(":");n.push({hostname:s,pathname:a})}}function s(e,t){return!(e.length>t.length)&&t.indexOf(e)===t.length-e.length}function c(e,t){return 0===e.indexOf("/")&&(e=e.substring(1)),0===t.indexOf("/")&&(t=t.substring(1)),""===e||e===t}},1687:(e,t,r)=>{"use strict";r.d(t,{Ak:()=>c,Ze:()=>l,x3:()=>d});var n=r(7836),i=r(1478),o=r(3606),a=r(860);const s={};function c(e,t){const r={staged:!1,priority:a.P[t]||0};u(e),s[e].get(t)||s[e].set(t,r)}function d(e,t){e&&s[e]&&(s[e].get(t)&&s[e].delete(t),h(e,t,!1),s[e].size&&f(e))}function u(e){if(!e)throw new Error("agentIdentifier required");s[e]||(s[e]=new Map)}function l(){let e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:"",t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:"feature",r=arguments.length>2&&void 0!==arguments[2]&&arguments[2];if(u(e),!e||!s[e].get(t)||r)return h(e,t);s[e].get(t).staged=!0,f(e)}function f(e){const t=Array.from(s[e]);t.every((e=>{let[t,r]=e;return r.staged}))&&(t.sort(((e,t)=>e[1].priority-t[1].priority)),t.forEach((t=>{let[r]=t;s[e].delete(r),h(e,r)})))}function h(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];const a=e?n.ee.get(e):n.ee,s=o.i.handlers;if(!a.aborted&&a.backlog&&s){if(r){const e=a.backlog[t],r=s[t];if(r){for(let t=0;e&&t<e.length;++t)g(e[t],r);(0,i.$)(r,(function(e,t){(0,i.$)(t,(function(t,r){r[0].on(e,r[1])}))}))}}a.isolatedBacklog||delete s[t],a.backlog[t]=null,a.emit("drain-"+t,[])}}function g(e,t){var r=e[1];(0,i.$)(t[r],(function(t,r){var n=e[0];if(r[0]===n){var i=r[1],o=e[3],a=e[2];i.apply(o,a)}}))}},7836:(e,t,r)=>{"use strict";r.d(t,{P:()=>c,ee:()=>d});var n=r(384),i=r(8990),o=r(2983),a=r(2646),s=r(5607);const c="nr@context:".concat(s.W),d=function e(t,r){var n={},s={},u={},l=!1;try{l=16===r.length&&(0,o.fr)(r).isolatedBacklog}catch(e){}var f={on:g,addEventListener:g,removeEventListener:function(e,t){var r=n[e];if(!r)return;for(var i=0;i<r.length;i++)r[i]===t&&r.splice(i,1)},emit:function(e,r,n,i,o){!1!==o&&(o=!0);if(d.aborted&&!i)return;t&&o&&t.emit(e,r,n);for(var a=h(n),c=p(e),u=c.length,l=0;l<u;l++)c[l].apply(a,r);var g=v()[s[e]];g&&g.push([f,e,r,a]);return a},get:m,listeners:p,context:h,buffer:function(e,t){const r=v();if(t=t||"feature",f.aborted)return;Object.entries(e||{}).forEach((e=>{let[n,i]=e;s[i]=t,t in r||(r[t]=[])}))},abort:function(){f._aborted=!0,Object.keys(f.backlog).forEach((e=>{delete f.backlog[e]}))},isBuffering:function(e){return!!v()[s[e]]},debugId:r,backlog:l?{}:t&&"object"==typeof t.backlog?t.backlog:{},isolatedBacklog:l};return Object.defineProperty(f,"aborted",{get:()=>{let e=f._aborted||!1;return e||(t&&(e=t.aborted),e)}}),f;function h(e){return e&&e instanceof a.y?e:e?(0,i.I)(e,c,(()=>new a.y(c))):new a.y(c)}function g(e,t){n[e]=p(e).concat(t)}function p(e){return n[e]||[]}function m(t){return u[t]=u[t]||e(f,t)}function v(){return f.backlog}}(void 0,"globalEE"),u=(0,n.Zm)();u.ee||(u.ee=d)},2646:(e,t,r)=>{"use strict";r.d(t,{y:()=>n});class n{constructor(e){this.contextId=e}}},9908:(e,t,r)=>{"use strict";r.d(t,{d:()=>n,p:()=>i});var n=r(7836).ee.get("handle");function i(e,t,r,i,o){o?(o.buffer([e],i),o.emit(e,t,r)):(n.buffer([e],i),n.emit(e,t,r))}},3606:(e,t,r)=>{"use strict";r.d(t,{i:()=>o});var n=r(9908);o.on=a;var i=o.handlers={};function o(e,t,r,o){a(o||n.d,i,e,t,r)}function a(e,t,r,i,o){o||(o="feature"),e||(e=n.d);var a=t[o]=t[o]||{};(a[r]=a[r]||[]).push([e,i])}},3878:(e,t,r)=>{"use strict";r.d(t,{DD:()=>c,jT:()=>a,sp:()=>s});var n=r(6154);let i=!1,o=!1;try{const e={get passive(){return i=!0,!1},get signal(){return o=!0,!1}};n.gm.addEventListener("test",null,e),n.gm.removeEventListener("test",null,e)}catch(e){}function a(e,t){return i||o?{capture:!!e,passive:i,signal:t}:!!e}function s(e,t){let r=arguments.length>2&&void 0!==arguments[2]&&arguments[2],n=arguments.length>3?arguments[3]:void 0;window.addEventListener(e,t,a(r,n))}function c(e,t){let r=arguments.length>2&&void 0!==arguments[2]&&arguments[2],n=arguments.length>3?arguments[3]:void 0;document.addEventListener(e,t,a(r,n))}},5607:(e,t,r)=>{"use strict";r.d(t,{W:()=>n});const n=(0,r(9566).bz)()},9566:(e,t,r)=>{"use strict";r.d(t,{LA:()=>s,ZF:()=>c,bz:()=>a,el:()=>d});var n=r(6154);const i="xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx";function o(e,t){return e?15&e[t]:16*Math.random()|0}function a(){const e=n.gm?.crypto||n.gm?.msCrypto;let t,r=0;return e&&e.getRandomValues&&(t=e.getRandomValues(new Uint8Array(30))),i.split("").map((e=>"x"===e?o(t,r++).toString(16):"y"===e?(3&o()|8).toString(16):e)).join("")}function s(e){const t=n.gm?.crypto||n.gm?.msCrypto;let r,i=0;t&&t.getRandomValues&&(r=t.getRandomValues(new Uint8Array(e)));const a=[];for(var s=0;s<e;s++)a.push(o(r,i++).toString(16));return a.join("")}function c(){return s(16)}function d(){return s(32)}},2614:(e,t,r)=>{"use strict";r.d(t,{BB:()=>a,H3:()=>n,g:()=>d,iL:()=>c,tS:()=>s,uh:()=>i,wk:()=>o});const n="NRBA",i="SESSION",o=144e5,a=18e5,s={STARTED:"session-started",PAUSE:"session-pause",RESET:"session-reset",RESUME:"session-resume",UPDATE:"session-update"},c={SAME_TAB:"same-tab",CROSS_TAB:"cross-tab"},d={OFF:0,FULL:1,ERROR:2}},1863:(e,t,r)=>{"use strict";function n(){return Math.floor(performance.now())}r.d(t,{t:()=>n})},7485:(e,t,r)=>{"use strict";r.d(t,{D:()=>i});var n=r(6154);function i(e){if(0===(e||"").indexOf("data:"))return{protocol:"data"};try{const t=new URL(e,location.href),r={port:t.port,hostname:t.hostname,pathname:t.pathname,search:t.search,protocol:t.protocol.slice(0,t.protocol.indexOf(":")),sameOrigin:t.protocol===n.gm?.location?.protocol&&t.host===n.gm?.location?.host};return r.port&&""!==r.port||("http:"===t.protocol&&(r.port="80"),"https:"===t.protocol&&(r.port="443")),r.pathname&&""!==r.pathname?r.pathname.startsWith("/")||(r.pathname="/".concat(r.pathname)):r.pathname="/",r}catch(e){return{}}}},944:(e,t,r)=>{"use strict";function n(e,t){"function"==typeof console.debug&&console.debug("New Relic Warning: https://github.com/newrelic/newrelic-browser-agent/blob/main/docs/warning-codes.md#".concat(e),t)}r.d(t,{R:()=>n})},5284:(e,t,r)=>{"use strict";r.d(t,{t:()=>c,B:()=>s});var n=r(7836),i=r(6154);const o="newrelic";const a=new Set,s={};function c(e,t){const r=n.ee.get(t);s[t]??={},e&&"object"==typeof e&&(a.has(t)||(r.emit("rumresp",[e]),s[t]=e,a.add(t),function(){let e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:{};try{i.gm.dispatchEvent(new CustomEvent(o,{detail:e}))}catch(e){}}({loaded:!0})))}},8990:(e,t,r)=>{"use strict";r.d(t,{I:()=>i});var n=Object.prototype.hasOwnProperty;function i(e,t,r){if(n.call(e,t))return e[t];var i=r();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:i,writable:!0,enumerable:!1}),i}catch(e){}return e[t]=i,i}},6389:(e,t,r)=>{"use strict";function n(e){var t=this;let r=arguments.length>1&&void 0!==arguments[1]?arguments[1]:500,n=arguments.length>2&&void 0!==arguments[2]?arguments[2]:{};const i=n?.leading||!1;let o;return function(){for(var n=arguments.length,a=new Array(n),s=0;s<n;s++)a[s]=arguments[s];i&&void 0===o&&(e.apply(t,a),o=setTimeout((()=>{o=clearTimeout(o)}),r)),i||(clearTimeout(o),o=setTimeout((()=>{e.apply(t,a)}),r))}}function i(e){var t=this;let r=!1;return function(){if(!r){r=!0;for(var n=arguments.length,i=new Array(n),o=0;o<n;o++)i[o]=arguments[o];e.apply(t,i)}}}r.d(t,{J:()=>i,s:()=>n})},1478:(e,t,r)=>{"use strict";r.d(t,{$:()=>n});const n=(e,t)=>Object.entries(e||{}).map((e=>{let[r,n]=e;return t(r,n)}))},3304:(e,t,r)=>{"use strict";r.d(t,{A:()=>o});var n=r(7836);const i=()=>{const e=new WeakSet;return(t,r)=>{if("object"==typeof r&&null!==r){if(e.has(r))return;e.add(r)}return r}};function o(e){try{return JSON.stringify(e,i())}catch(e){try{n.ee.emit("internal-error",[e])}catch(e){}}}},5289:(e,t,r)=>{"use strict";r.d(t,{GG:()=>o,sB:()=>a});var n=r(3878);function i(){return"undefined"==typeof document||"complete"===document.readyState}function o(e,t){if(i())return e();(0,n.sp)("load",e,t)}function a(e){if(i())return e();(0,n.DD)("DOMContentLoaded",e)}},384:(e,t,r)=>{"use strict";r.d(t,{NT:()=>o,US:()=>u,Zm:()=>a,bQ:()=>c,dV:()=>s,nY:()=>d,pV:()=>l});var n=r(6154),i=r(1863);const o={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net"};function a(){return n.gm.NREUM||(n.gm.NREUM={}),void 0===n.gm.newrelic&&(n.gm.newrelic=n.gm.NREUM),n.gm.NREUM}function s(){let e=a();return e.o||(e.o={ST:n.gm.setTimeout,SI:n.gm.setImmediate,CT:n.gm.clearTimeout,XHR:n.gm.XMLHttpRequest,REQ:n.gm.Request,EV:n.gm.Event,PR:n.gm.Promise,MO:n.gm.MutationObserver,FETCH:n.gm.fetch}),e}function c(e,t){let r=a();r.initializedAgents??={},t.initializedAt={ms:(0,i.t)(),date:new Date},r.initializedAgents[e]=t}function d(e){let t=a();return t.initializedAgents?.[e]}function u(e,t){a()[e]=t}function l(){return function(){let e=a();const t=e.info||{};e.info={beacon:o.beacon,errorBeacon:o.errorBeacon,...t}}(),function(){let e=a();const t=e.init||{};e.init={...t}}(),s(),function(){let e=a();const t=e.loader_config||{};e.loader_config={...t}}(),a()}},2843:(e,t,r)=>{"use strict";r.d(t,{u:()=>i});var n=r(3878);function i(e){let t=arguments.length>1&&void 0!==arguments[1]&&arguments[1],r=arguments.length>2?arguments[2]:void 0,i=arguments.length>3?arguments[3]:void 0;(0,n.DD)("visibilitychange",(function(){if(t)return void("hidden"===document.visibilityState&&e());e(document.visibilityState)}),r,i)}},8941:(e,t,r)=>{"use strict";r.d(t,{um:()=>f,NZ:()=>x,vC:()=>A,bX:()=>N});var n=r(7836),i=r(3434),o=r(8990),a=r(6154);const s={},c=a.gm.XMLHttpRequest,d="addEventListener",u="removeEventListener",l="nr@wrapped:".concat(n.P);function f(e){var t=function(e){return(e||n.ee).get("events")}(e);if(s[t.debugId]++)return t;s[t.debugId]=1;var r=(0,i.YM)(t,!0);function f(e){r.inPlace(e,[d,u],"-",g)}function g(e,t){return e[1]}return"getPrototypeOf"in Object&&(a.RI&&h(document,f),h(a.gm,f),h(c.prototype,f)),t.on(d+"-start",(function(e,t){var n=e[1];if(null!==n&&("function"==typeof n||"object"==typeof n)){var i=(0,o.I)(n,l,(function(){var e={object:function(){if("function"!=typeof n.handleEvent)return;return n.handleEvent.apply(n,arguments)},function:n}[typeof n];return e?r(e,"fn-",null,e.name||"anonymous"):n}));this.wrapped=e[1]=i}})),t.on(u+"-start",(function(e){e[1]=this.wrapped||e[1]})),t}function h(e,t){let r=e;for(;"object"==typeof r&&!Object.prototype.hasOwnProperty.call(r,d);)r=Object.getPrototypeOf(r);for(var n=arguments.length,i=new Array(n>2?n-2:0),o=2;o<n;o++)i[o-2]=arguments[o];r&&t(r,...i)}var g="fetch-",p=g+"body-",m=["arrayBuffer","blob","json","text","formData"],v=a.gm.Request,b=a.gm.Response,y="prototype";const R={};function x(e){const t=function(e){return(e||n.ee).get("fetch")}(e);if(!(v&&b&&a.gm.fetch))return t;if(R[t.debugId]++)return t;function r(e,r,i){var o=e[r];"function"==typeof o&&(e[r]=function(){var e,r=[...arguments],a={};t.emit(i+"before-start",[r],a),a[n.P]&&a[n.P].dt&&(e=a[n.P].dt);var s=o.apply(this,r);return t.emit(i+"start",[r,e],s),s.then((function(e){return t.emit(i+"end",[null,e],s),e}),(function(e){throw t.emit(i+"end",[e],s),e}))})}return R[t.debugId]=1,m.forEach((e=>{r(v[y],e,p),r(b[y],e,p)})),r(a.gm,"fetch",g),t.on(g+"end",(function(e,r){var n=this;if(r){var i=r.headers.get("content-length");null!==i&&(n.rxSize=i),t.emit(g+"done",[null,r],n)}else t.emit(g+"done",[e],n)})),t}const w={},T=["pushState","replaceState"];function A(e){const t=function(e){return(e||n.ee).get("history")}(e);return!a.RI||w[t.debugId]++||(w[t.debugId]=1,(0,i.YM)(t).inPlace(window.history,T,"-")),t}var S=r(3878);var E=r(944);const _={},O=["open","send"];function N(e){var t=e||n.ee;const r=function(e){return(e||n.ee).get("xhr")}(t);if(_[r.debugId]++)return r;_[r.debugId]=1,f(t);var o=(0,i.YM)(r),s=a.gm.XMLHttpRequest,c=a.gm.MutationObserver,d=a.gm.Promise,u=a.gm.setInterval,l="readystatechange",h=["onload","onerror","onabort","onloadstart","onloadend","onprogress","ontimeout"],g=[],p=a.gm.XMLHttpRequest=function(e){const t=new s(e),n=r.context(t);try{r.emit("new-xhr",[t],n),t.addEventListener(l,(i=n,function(){var e=this;e.readyState>3&&!i.resolved&&(i.resolved=!0,r.emit("xhr-resolved",[],e)),o.inPlace(e,h,"fn-",x)}),(0,S.jT)(!1))}catch(e){(0,E.R)(15,e);try{r.emit("internal-error",[e])}catch(e){}}var i;return t};function m(e,t){o.inPlace(t,["onreadystatechange"],"fn-",x)}if(function(e,t){for(var r in e)t[r]=e[r]}(s,p),p.prototype=s.prototype,o.inPlace(p.prototype,O,"-xhr-",x),r.on("send-xhr-start",(function(e,t){m(e,t),function(e){g.push(e),c&&(v?v.then(R):u?u(R):(b=-b,y.data=b))}(t)})),r.on("open-xhr-start",m),c){var v=d&&d.resolve();if(!u&&!d){var b=1,y=document.createTextNode(b);new c(R).observe(y,{characterData:!0})}}else t.on("fn-end",(function(e){e[0]&&e[0].type===l||R()}));function R(){for(var e=0;e<g.length;e++)m(0,g[e]);g.length&&(g=[])}function x(e,t){return t}return r}},3434:(e,t,r)=>{"use strict";r.d(t,{YM:()=>c});var n=r(7836),i=r(5607);const o="nr@original:".concat(i.W);var a=Object.prototype.hasOwnProperty,s=!1;function c(e,t){return e||(e=n.ee),r.inPlace=function(e,t,n,i,o){n||(n="");const a="-"===n.charAt(0);for(let s=0;s<t.length;s++){const c=t[s],d=e[c];u(d)||(e[c]=r(d,a?c+n:n,i,c,o))}},r.flag=o,r;function r(t,r,n,s,c){return u(t)?t:(r||(r=""),nrWrapper[o]=t,function(e,t,r){if(Object.defineProperty&&Object.keys)try{return Object.keys(e).forEach((function(r){Object.defineProperty(t,r,{get:function(){return e[r]},set:function(t){return e[r]=t,t}})})),t}catch(e){d([e],r)}for(var n in e)a.call(e,n)&&(t[n]=e[n])}(t,nrWrapper,e),nrWrapper);function nrWrapper(){var o,a,u,l;try{a=this,o=[...arguments],u="function"==typeof n?n(o,a):n||{}}catch(t){d([t,"",[o,a,s],u],e)}i(r+"start",[o,a,s],u,c);try{return l=t.apply(a,o)}catch(e){throw i(r+"err",[o,a,e],u,c),e}finally{i(r+"end",[o,a,l],u,c)}}}function i(r,n,i,o){if(!s||t){var a=s;s=!0;try{e.emit(r,n,i,t,o)}catch(t){d([t,r,n,i],e)}s=a}}}function d(e,t){t||(t=n.ee);try{t.emit("internal-error",e)}catch(e){}}function u(e){return!(e&&"function"==typeof e&&e.apply&&!e[o])}},9300:(e,t,r)=>{"use strict";r.d(t,{T:()=>n});const n=r(860).K.ajax},6774:(e,t,r)=>{"use strict";r.d(t,{T:()=>n});const n=r(860).K.jserrors},993:(e,t,r)=>{"use strict";r.d(t,{ET:()=>o,It:()=>s,TZ:()=>a,p_:()=>i});var n=r(860);const i={ERROR:"ERROR",WARN:"WARN",INFO:"INFO",DEBUG:"DEBUG",TRACE:"TRACE"},o="log",a=n.K.logging,s=1e6},3785:(e,t,r)=>{"use strict";r.d(t,{R:()=>c,b:()=>d});var n=r(9908),i=r(1863),o=r(860),a=r(3969),s=r(993);function c(e,t){let r=arguments.length>2&&void 0!==arguments[2]?arguments[2]:{},c=arguments.length>3&&void 0!==arguments[3]?arguments[3]:s.p_.INFO;(0,n.p)(a.xV,["API/logging/".concat(c.toLowerCase(),"/called")],void 0,o.K.metrics,e),(0,n.p)(s.ET,[(0,i.t)(),t,r,c],void 0,o.K.logging,e)}function d(e){return"string"==typeof e&&Object.values(s.p_).some((t=>t===e))}},3969:(e,t,r)=>{"use strict";r.d(t,{TZ:()=>n,XG:()=>s,rs:()=>i,xV:()=>a,z_:()=>o});const n=r(860).K.metrics,i="sm",o="cm",a="storeSupportabilityMetrics",s="storeEventMetrics"},8166:(e,t,r)=>{"use strict";r.d(t,{T:()=>n});const n=r(860).K.pageAction},6630:(e,t,r)=>{"use strict";r.d(t,{T:()=>n});const n=r(860).K.pageViewEvent},782:(e,t,r)=>{"use strict";r.d(t,{T:()=>n});const n=r(860).K.pageViewTiming},6344:(e,t,r)=>{"use strict";r.d(t,{BB:()=>f,G4:()=>o,It:()=>c,No:()=>d,Qb:()=>h,TZ:()=>i,Ug:()=>a,_s:()=>s,bc:()=>l,yP:()=>u});var n=r(2614);const i=r(860).K.sessionReplay,o={RECORD:"recordReplay",PAUSE:"pauseReplay",REPLAY_RUNNING:"replayRunning",ERROR_DURING_REPLAY:"errorDuringReplay"},a=.12,s={DomContentLoaded:0,Load:1,FullSnapshot:2,IncrementalSnapshot:3,Meta:4,Custom:5},c=1e6,d=64e3,u={[n.g.ERROR]:15e3,[n.g.FULL]:3e5,[n.g.OFF]:0},l={RESET:{message:"Session was reset",sm:"Reset"},IMPORT:{message:"Recorder failed to import",sm:"Import"},TOO_MANY:{message:"429: Too Many Requests",sm:"Too-Many"},TOO_BIG:{message:"Payload was too large",sm:"Too-Big"},CROSS_TAB:{message:"Session Entity was set to OFF on another tab",sm:"Cross-Tab"},ENTITLEMENTS:{message:"Session Replay is not allowed and will not be started",sm:"Entitlement"}},f=5e3,h={API:"api"}},5270:(e,t,r)=>{"use strict";r.d(t,{Aw:()=>s,CT:()=>c,SR:()=>a});var n=r(2983),i=r(7767),o=r(6154);function a(e){return!!n.hR.MO&&(0,i.V)(e)&&!0===(0,n.gD)(e,"session_trace.enabled")}function s(e){return!0===(0,n.gD)(e,"session_replay.preload")&&a(e)}function c(e,t){const r=t.correctAbsoluteTimestamp(e);return{originalTimestamp:e,correctedTimestamp:r,timestampDiff:e-r,originTime:o.WN,correctedOriginTime:t.correctedOriginTime,originTimeDiff:Math.floor(o.WN-t.correctedOriginTime)}}},3738:(e,t,r)=>{"use strict";r.d(t,{He:()=>i,Kp:()=>s,Lc:()=>d,Rz:()=>u,TZ:()=>n,bD:()=>o,d3:()=>a,jx:()=>l,uP:()=>c});const n=r(860).K.sessionTrace,i="bstResource",o="resource",a="-start",s="-end",c="fn"+a,d="fn"+s,u="pushState",l=1e3},4234:(e,t,r)=>{"use strict";r.d(t,{W:()=>i});var n=r(7836);class i{constructor(e,t,r){this.agentIdentifier=e,this.aggregator=t,this.ee=n.ee.get(e),this.featureName=r,this.blocked=!1}}},7767:(e,t,r)=>{"use strict";r.d(t,{V:()=>o});var n=r(2983),i=r(6154);const o=e=>i.RI&&!0===(0,n.gD)(e,"privacy.cookies_enabled")},425:(e,t,r)=>{"use strict";r.d(t,{j:()=>O});var n=r(860),i=r(2983),o=r(9908),a=r(7836),s=r(1687),c=r(5289),d=r(6154),u=r(944),l=r(3969),f=r(384),h=r(6344);const g=["setErrorHandler","finished","addToTrace","addRelease","addPageAction","setCurrentRouteName","setPageViewName","setCustomAttribute","interaction","noticeError","setUserId","setApplicationVersion","start",h.G4.RECORD,h.G4.PAUSE,"log","wrapLogger"],p=["setErrorHandler","finished","addToTrace","addRelease"];var m=r(1863),v=r(2614),b=r(993),y=r(3785),R=r(2646),x=r(3434);function w(e,t,r,n){if("object"!=typeof t||!t||"string"!=typeof r||!r||"function"!=typeof t[r])return(0,u.R)(29);const i=function(e){return(e||a.ee).get("logger")}(e),o=(0,x.YM)(i),s=new R.y(a.P);return s.level=n.level,s.customAttributes=n.customAttributes,o.inPlace(t,[r],"wrap-logger-",s),i}function T(){const e=(0,f.pV)();g.forEach((t=>{e[t]=function(){for(var r=arguments.length,n=new Array(r),i=0;i<r;i++)n[i]=arguments[i];return function(t){for(var r=arguments.length,n=new Array(r>1?r-1:0),i=1;i<r;i++)n[i-1]=arguments[i];let o=[];return Object.values(e.initializedAgents).forEach((e=>{e&&e.api?e.exposed&&e.api[t]&&o.push(e.api[t](...n)):(0,u.R)(38,t)})),o.length>1?o:o[0]}(t,...n)}}))}const A={};var S=r(5284);const E=e=>{const t=e.startsWith("http");e+="/",r.p=t?e:"https://"+e};let _=!1;function O(e){let t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{},g=arguments.length>2?arguments[2]:void 0,R=arguments.length>3?arguments[3]:void 0,{init:x,info:O,loader_config:N,runtime:I={loaderType:g},exposed:P=!0}=t;const j=(0,f.pV)();O||(x=j.init,O=j.info,N=j.loader_config),(0,i.xN)(e.agentIdentifier,x||{}),(0,i.aN)(e.agentIdentifier,N||{}),O.jsAttributes??={},d.bv&&(O.jsAttributes.isWorker=!0),(0,i.x1)(e.agentIdentifier,O);const C=(0,i.D0)(e.agentIdentifier),k=[O.beacon,O.errorBeacon];_||(C.proxy.assets&&(E(C.proxy.assets),k.push(C.proxy.assets)),C.proxy.beacon&&k.push(C.proxy.beacon),T(),(0,f.US)("activatedFeatures",S.B),e.runSoftNavOverSpa&&=!0===C.soft_navigations.enabled&&C.feature_flags.includes("soft_nav")),I.denyList=[...C.ajax.deny_list||[],...C.ajax.block_internal?k:[]],I.ptid=e.agentIdentifier,(0,i.V)(e.agentIdentifier,I),void 0===e.api&&(e.api=function(e,t){let f=arguments.length>2&&void 0!==arguments[2]&&arguments[2];t||(0,s.Ak)(e,"api");const g={};var R=a.ee.get(e),x=R.get("tracer");A[e]=v.g.OFF,R.on(h.G4.REPLAY_RUNNING,(t=>{A[e]=t}));var T="api-",S=T+"ixn-";function E(t,r,n,o){const a=(0,i.Vp)(e);return null===r?delete a.jsAttributes[t]:(0,i.x1)(e,{...a,jsAttributes:{...a.jsAttributes,[t]:r}}),N(T,n,!0,o||null===r?"session":void 0)(t,r)}function _(){}g.log=function(e){let{customAttributes:t={},level:r=b.p_.INFO}=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{};(0,o.p)(l.xV,["API/log/called"],void 0,n.K.metrics,R),(0,y.R)(R,e,t,r)},g.wrapLogger=function(e,t){let{customAttributes:r={},level:i=b.p_.INFO}=arguments.length>2&&void 0!==arguments[2]?arguments[2]:{};(0,o.p)(l.xV,["API/wrapLogger/called"],void 0,n.K.metrics,R),w(R,e,t,{customAttributes:r,level:i})},p.forEach((e=>{g[e]=N(T,e,!0,"api")})),g.addPageAction=N(T,"addPageAction",!0,n.K.pageAction),g.setPageViewName=function(t,r){if("string"==typeof t)return"/"!==t.charAt(0)&&(t="/"+t),(0,i.fr)(e).customTransaction=(r||"http://custom.transaction")+t,N(T,"setPageViewName",!0)()},g.setCustomAttribute=function(e,t){let r=arguments.length>2&&void 0!==arguments[2]&&arguments[2];if("string"==typeof e){if(["string","number","boolean"].includes(typeof t)||null===t)return E(e,t,"setCustomAttribute",r);(0,u.R)(40,typeof t)}else(0,u.R)(39,typeof e)},g.setUserId=function(e){if("string"==typeof e||null===e)return E("enduser.id",e,"setUserId",!0);(0,u.R)(41,typeof e)},g.setApplicationVersion=function(e){if("string"==typeof e||null===e)return E("application.version",e,"setApplicationVersion",!1);(0,u.R)(42,typeof e)},g.start=()=>{try{(0,o.p)(l.xV,["API/start/called"],void 0,n.K.metrics,R),R.emit("manual-start-all")}catch(e){(0,u.R)(23,e)}},g[h.G4.RECORD]=function(){(0,o.p)(l.xV,["API/recordReplay/called"],void 0,n.K.metrics,R),(0,o.p)(h.G4.RECORD,[],void 0,n.K.sessionReplay,R)},g[h.G4.PAUSE]=function(){(0,o.p)(l.xV,["API/pauseReplay/called"],void 0,n.K.metrics,R),(0,o.p)(h.G4.PAUSE,[],void 0,n.K.sessionReplay,R)},g.interaction=function(e){return(new _).get("object"==typeof e?e:{})};const O=_.prototype={createTracer:function(e,t){var r={},i=this,a="function"==typeof t;return(0,o.p)(l.xV,["API/createTracer/called"],void 0,n.K.metrics,R),f||(0,o.p)(S+"tracer",[(0,m.t)(),e,r],i,n.K.spa,R),function(){if(x.emit((a?"":"no-")+"fn-start",[(0,m.t)(),i,a],r),a)try{return t.apply(this,arguments)}catch(e){const t="string"==typeof e?new Error(e):e;throw x.emit("fn-err",[arguments,this,t],r),t}finally{x.emit("fn-end",[(0,m.t)()],r)}}}};function N(e,t,r,i){return function(){return(0,o.p)(l.xV,["API/"+t+"/called"],void 0,n.K.metrics,R),i&&(0,o.p)(e+t,[(0,m.t)(),...arguments],r?null:this,i,R),r?void 0:this}}function I(){r.e(891).then(r.bind(r,8778)).then((t=>{let{setAPI:r}=t;r(e),(0,s.Ze)(e,"api")})).catch((e=>{(0,u.R)(27,e),R.abort()}))}return["actionText","setName","setAttribute","save","ignore","onEnd","getContext","end","get"].forEach((e=>{O[e]=N(S,e,void 0,f?n.K.softNav:n.K.spa)})),g.setCurrentRouteName=f?N(S,"routeName",void 0,n.K.softNav):N(T,"routeName",!0,n.K.spa),g.noticeError=function(t,r){"string"==typeof t&&(t=new Error(t)),(0,o.p)(l.xV,["API/noticeError/called"],void 0,n.K.metrics,R),(0,o.p)("err",[t,(0,m.t)(),!1,r,!!A[e]],void 0,n.K.jserrors,R)},d.RI?(0,c.GG)((()=>I()),!0):I(),g}(e.agentIdentifier,R,e.runSoftNavOverSpa)),void 0===e.exposed&&(e.exposed=P),_=!0}},8374:(e,t,r)=>{r.nc=(()=>{try{return document?.currentScript?.nonce}catch(e){}return""})()},860:(e,t,r)=>{"use strict";r.d(t,{K:()=>n,P:()=>i});const n={ajax:"ajax",jserrors:"jserrors",logging:"logging",metrics:"metrics",pageAction:"page_action",pageViewEvent:"page_view_event",pageViewTiming:"page_view_timing",sessionReplay:"session_replay",sessionTrace:"session_trace",softNav:"soft_navigations",spa:"spa"},i={[n.pageViewEvent]:1,[n.pageViewTiming]:2,[n.metrics]:3,[n.jserrors]:4,[n.spa]:5,[n.ajax]:6,[n.sessionTrace]:7,[n.pageAction]:8,[n.softNav]:9,[n.sessionReplay]:10,[n.logging]:11}}},n={};function i(e){var t=n[e];if(void 0!==t)return t.exports;var o=n[e]={exports:{}};return r[e](o,o.exports,i),o.exports}i.m=r,i.d=(e,t)=>{for(var r in t)i.o(t,r)&&!i.o(e,r)&&Object.defineProperty(e,r,{enumerable:!0,get:t[r]})},i.f={},i.e=e=>Promise.all(Object.keys(i.f).reduce(((t,r)=>(i.f[r](e,t),t)),[])),i.u=e=>({95:"nr-full-compressor",222:"nr-full-recorder",891:"nr-full"}[e]+"-1.263.0.min.js"),i.o=(e,t)=>Object.prototype.hasOwnProperty.call(e,t),e={},t="NRBA-1.263.0.PROD:",i.l=(r,n,o,a)=>{if(e[r])e[r].push(n);else{var s,c;if(void 0!==o)for(var d=document.getElementsByTagName("script"),u=0;u<d.length;u++){var l=d[u];if(l.getAttribute("src")==r||l.getAttribute("data-webpack")==t+o){s=l;break}}if(!s){c=!0;var f={891:"sha512-d7roS9WdU7IareWVw0crL+Gwn1rPlPzp4BEGmGITDdhFxWCqmBF6LKSFG4JAEkKs3XDCOnrh93I/K4+pWfsSGA==",222:"sha512-RS0HunhhKxWyjerl4PQPpxEoMUWYX2tT/ILMgMoKDJicRbyr1/OGeOhc8eV3wGUOfp5aGl94fplS6uUQlzGH2Q==",95:"sha512-eko5mWQmXHOs83sLwfymAqhi1ZPnz/kmJDtpJ+CS5xicLpVgP0J+lgl1KmoVTWYYVx5vUHrmKo9HbcZI8HhlCw=="};(s=document.createElement("script")).charset="utf-8",s.timeout=120,i.nc&&s.setAttribute("nonce",i.nc),s.setAttribute("data-webpack",t+o),s.src=r,0!==s.src.indexOf(window.location.origin+"/")&&(s.crossOrigin="anonymous"),f[a]&&(s.integrity=f[a])}e[r]=[n];var h=(t,n)=>{s.onerror=s.onload=null,clearTimeout(g);var i=e[r];if(delete e[r],s.parentNode&&s.parentNode.removeChild(s),i&&i.forEach((e=>e(n))),t)return t(n)},g=setTimeout(h.bind(null,void 0,{type:"timeout",target:s}),12e4);s.onerror=h.bind(null,s.onerror),s.onload=h.bind(null,s.onload),c&&document.head.appendChild(s)}},i.r=e=>{"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},i.p="https://js-agent.newrelic.com/",(()=>{var e={959:0,85:0};i.f.j=(t,r)=>{var n=i.o(e,t)?e[t]:void 0;if(0!==n)if(n)r.push(n[2]);else{var o=new Promise(((r,i)=>n=e[t]=[r,i]));r.push(n[2]=o);var a=i.p+i.u(t),s=new Error;i.l(a,(r=>{if(i.o(e,t)&&(0!==(n=e[t])&&(e[t]=void 0),n)){var o=r&&("load"===r.type?"missing":r.type),a=r&&r.target&&r.target.src;s.message="Loading chunk "+t+" failed.\n("+o+": "+a+")",s.name="ChunkLoadError",s.type=o,s.request=a,n[1](s)}}),"chunk-"+t,t)}};var t=(t,r)=>{var n,o,[a,s,c]=r,d=0;if(a.some((t=>0!==e[t]))){for(n in s)i.o(s,n)&&(i.m[n]=s[n]);if(c)c(i)}for(t&&t(r);d<a.length;d++)o=a[d],i.o(e,o)&&e[o]&&e[o][0](),e[o]=0},r=self["webpackChunk:NRBA-1.263.0.PROD"]=self["webpackChunk:NRBA-1.263.0.PROD"]||[];r.forEach(t.bind(null,0)),r.push=t.bind(null,r.push.bind(r))})(),(()=>{"use strict";i(8374);var e=i(944),t=i(6344),r=i(9566),n=i(7836);class o{agentIdentifier;constructor(){let e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:(0,r.LA)(16);this.agentIdentifier=e,this.ee=n.ee.get(e)}#e(t){for(var r=arguments.length,n=new Array(r>1?r-1:0),i=1;i<r;i++)n[i-1]=arguments[i];if("function"==typeof this.api?.[t])return this.api[t](...n);(0,e.R)(35,t)}addPageAction(e,t){return this.#e("addPageAction",e,t)}setPageViewName(e,t){return this.#e("setPageViewName",e,t)}setCustomAttribute(e,t,r){return this.#e("setCustomAttribute",e,t,r)}noticeError(e,t){return this.#e("noticeError",e,t)}setUserId(e){return this.#e("setUserId",e)}setApplicationVersion(e){return this.#e("setApplicationVersion",e)}setErrorHandler(e){return this.#e("setErrorHandler",e)}finished(e){return this.#e("finished",e)}addRelease(e,t){return this.#e("addRelease",e,t)}start(e){return this.#e("start",e)}recordReplay(){return this.#e(t.G4.RECORD)}pauseReplay(){return this.#e(t.G4.PAUSE)}addToTrace(e){return this.#e("addToTrace",e)}setCurrentRouteName(e){return this.#e("setCurrentRouteName",e)}interaction(){return this.#e("interaction")}log(e,t){return this.#e("logInfo",e,t)}wrapLogger(e,t,r){return this.#e("wrapLogger",e,t,r)}}var a=i(860),s=i(2983);const c=Object.values(a.K);function d(e){const t={};return c.forEach((r=>{t[r]=function(e,t){return!0===(0,s.gD)(t,"".concat(e,".enabled"))}(r,e)})),t}var u=i(425);var l=i(1687),f=i(4234),h=i(5289),g=i(6154),p=i(5270),m=i(7767),v=i(6389);class b extends f.W{constructor(e,t,r){let n=!(arguments.length>3&&void 0!==arguments[3])||arguments[3];super(e,t,r),this.auto=n,this.abortHandler=void 0,this.featAggregate=void 0,this.onAggregateImported=void 0,!1===(0,s.gD)(this.agentIdentifier,"".concat(this.featureName,".autoStart"))&&(this.auto=!1),this.auto?(0,l.Ak)(e,r):this.ee.on("manual-start-all",(0,v.J)((()=>{(0,l.Ak)(this.agentIdentifier,this.featureName),this.auto=!0,this.importAggregator()})))}importAggregator(){let t,r=arguments.length>0&&void 0!==arguments[0]?arguments[0]:{};if(this.featAggregate||!this.auto)return;this.onAggregateImported=new Promise((e=>{t=e}));const n=async()=>{let n;try{if((0,m.V)(this.agentIdentifier)){const{setupAgentSession:e}=await i.e(891).then(i.bind(i,6526));n=e(this.agentIdentifier)}}catch(t){(0,e.R)(20,t),this.ee.emit("internal-error",[t]),this.featureName===a.K.sessionReplay&&this.abortHandler?.()}try{if(!this.#t(this.featureName,n))return(0,l.Ze)(this.agentIdentifier,this.featureName),void t(!1);const{lazyFeatureLoader:e}=await i.e(891).then(i.bind(i,6103)),{Aggregate:o}=await e(this.featureName,"aggregate");this.featAggregate=new o(this.agentIdentifier,this.aggregator,r),t(!0)}catch(r){(0,e.R)(34,r),this.abortHandler?.(),(0,l.Ze)(this.agentIdentifier,this.featureName,!0),t(!1),this.ee&&this.ee.abort()}};g.RI?(0,h.GG)((()=>n()),!0):n()}#t(e,t){switch(e){case a.K.sessionReplay:return(0,p.SR)(this.agentIdentifier)&&!!t;case a.K.sessionTrace:return!!t;default:return!0}}}var y=i(6630);class R extends b{static featureName=y.T;constructor(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,t,y.T,r),this.importAggregator()}}var x=i(4777),w=i(1478);class T extends x.J{constructor(e){super(e),this.aggregatedData={}}store(e,t,r,n,i){var o=this.getBucket(e,t,r,i);return o.metrics=function(e,t){t||(t={count:0});return t.count+=1,(0,w.$)(e,(function(e,r){t[e]=A(r,t[e])})),t}(n,o.metrics),o}merge(e,t,r,n,i){var o=this.getBucket(e,t,n,i);if(o.metrics){var a=o.metrics;a.count+=r.count,(0,w.$)(r,(function(e,t){if("count"!==e){var n=a[e],i=r[e];i&&!i.c?a[e]=A(i.t,n):a[e]=function(e,t){if(!t)return e;t.c||(t=S(t.t));return t.min=Math.min(e.min,t.min),t.max=Math.max(e.max,t.max),t.t+=e.t,t.sos+=e.sos,t.c+=e.c,t}(i,a[e])}}))}else o.metrics=r}storeMetric(e,t,r,n){var i=this.getBucket(e,t,r);return i.stats=A(n,i.stats),i}getBucket(e,t,r,n){this.aggregatedData[e]||(this.aggregatedData[e]={});var i=this.aggregatedData[e][t];return i||(i=this.aggregatedData[e][t]={params:r||{}},n&&(i.custom=n)),i}get(e,t){return t?this.aggregatedData[e]&&this.aggregatedData[e][t]:this.aggregatedData[e]}take(e){for(var t={},r="",n=!1,i=0;i<e.length;i++)t[r=e[i]]=Object.values(this.aggregatedData[r]||{}),t[r].length&&(n=!0),delete this.aggregatedData[r];return n?t:null}}function A(e,t){return null==e?function(e){e?e.c++:e={c:1};return e}(t):t?(t.c||(t=S(t.t)),t.c+=1,t.t+=e,t.sos+=e*e,e>t.max&&(t.max=e),e<t.min&&(t.min=e),t):{t:e}}function S(e){return{t:e,min:e,max:e,sos:e*e,c:1}}var E=i(384);var _=i(9908),O=i(2843),N=i(3878),I=i(782),P=i(1863);class j extends b{static featureName=I.T;constructor(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,t,I.T,r),g.RI&&((0,O.u)((()=>(0,_.p)("docHidden",[(0,P.t)()],void 0,I.T,this.ee)),!0),(0,N.sp)("pagehide",(()=>(0,_.p)("winPagehide",[(0,P.t)()],void 0,I.T,this.ee))),this.importAggregator())}}var C=i(3969);class k extends b{static featureName=C.TZ;constructor(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,t,C.TZ,r),this.importAggregator()}}var D=i(6774),H=i(3304);class L{constructor(e,t,r,n,i){this.name="UncaughtError",this.message="string"==typeof e?e:(0,H.A)(e),this.sourceURL=t,this.line=r,this.column=n,this.__newrelic=i}}function M(e){return V(e)?e:new L(void 0!==e?.message?e.message:e,e?.filename||e?.sourceURL,e?.lineno||e?.line,e?.colno||e?.col,e?.__newrelic)}function K(e){let t="Unhandled Promise Rejection";if(V(e?.reason))try{return e.reason.message=t+": "+e.reason.message,M(e.reason)}catch(t){return M(e.reason)}if(void 0===e.reason)return M(t);const r=M(e.reason);return r.message=t+": "+r?.message,r}function U(e){if(e.error instanceof SyntaxError&&!/:\d+$/.test(e.error.stack?.trim())){const t=new L(e.message,e.filename,e.lineno,e.colno,e.error.__newrelic);return t.name=SyntaxError.name,t}return V(e.error)?e.error:M(e)}function V(e){return e instanceof Error&&!!e.stack}class B extends b{static featureName=D.T;#r=!1;constructor(e,r){let n=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,r,D.T,n);try{this.removeOnAbort=new AbortController}catch(e){}this.ee.on("internal-error",(e=>{this.abortHandler&&(0,_.p)("ierr",[M(e),(0,P.t)(),!0,{},this.#r],void 0,this.featureName,this.ee)})),this.ee.on(t.G4.REPLAY_RUNNING,(e=>{this.#r=e})),g.gm.addEventListener("unhandledrejection",(e=>{this.abortHandler&&(0,_.p)("err",[K(e),(0,P.t)(),!1,{unhandledPromiseRejection:1},this.#r],void 0,this.featureName,this.ee)}),(0,N.jT)(!1,this.removeOnAbort?.signal)),g.gm.addEventListener("error",(e=>{this.abortHandler&&(0,_.p)("err",[U(e),(0,P.t)(),!1,{},this.#r],void 0,this.featureName,this.ee)}),(0,N.jT)(!1,this.removeOnAbort?.signal)),this.abortHandler=this.#n,this.importAggregator()}#n(){this.removeOnAbort?.abort(),this.abortHandler=void 0}}var G=i(8990);let F=1;const z="nr@id";function W(e){const t=typeof e;return!e||"object"!==t&&"function"!==t?-1:e===g.gm?0:(0,G.I)(e,z,(function(){return F++}))}function q(e){if("string"==typeof e&&e.length)return e.length;if("object"==typeof e){if("undefined"!=typeof ArrayBuffer&&e instanceof ArrayBuffer&&e.byteLength)return e.byteLength;if("undefined"!=typeof Blob&&e instanceof Blob&&e.size)return e.size;if(!("undefined"!=typeof FormData&&e instanceof FormData))try{return(0,H.A)(e).length}catch(e){return}}}var Z=i(8941),Y=i(7485);class X{constructor(e){this.agentIdentifier=e}generateTracePayload(e){if(!this.shouldGenerateTrace(e))return null;var t=(0,s.oC)(this.agentIdentifier);if(!t)return null;var n=(t.accountID||"").toString()||null,i=(t.agentID||"").toString()||null,o=(t.trustKey||"").toString()||null;if(!n||!i)return null;var a=(0,r.ZF)(),c=(0,r.el)(),d=Date.now(),u={spanId:a,traceId:c,timestamp:d};return(e.sameOrigin||this.isAllowedOrigin(e)&&this.useTraceContextHeadersForCors())&&(u.traceContextParentHeader=this.generateTraceContextParentHeader(a,c),u.traceContextStateHeader=this.generateTraceContextStateHeader(a,d,n,i,o)),(e.sameOrigin&&!this.excludeNewrelicHeader()||!e.sameOrigin&&this.isAllowedOrigin(e)&&this.useNewrelicHeaderForCors())&&(u.newrelicHeader=this.generateTraceHeader(a,c,d,n,i,o)),u}generateTraceContextParentHeader(e,t){return"00-"+t+"-"+e+"-01"}generateTraceContextStateHeader(e,t,r,n,i){return i+"@nr=0-1-"+r+"-"+n+"-"+e+"----"+t}generateTraceHeader(e,t,r,n,i,o){if(!("function"==typeof g.gm?.btoa))return null;var a={v:[0,1],d:{ty:"Browser",ac:n,ap:i,id:e,tr:t,ti:r}};return o&&n!==o&&(a.d.tk=o),btoa((0,H.A)(a))}shouldGenerateTrace(e){return this.isDtEnabled()&&this.isAllowedOrigin(e)}isAllowedOrigin(e){var t=!1,r={};if((0,s.gD)(this.agentIdentifier,"distributed_tracing")&&(r=(0,s.D0)(this.agentIdentifier).distributed_tracing),e.sameOrigin)t=!0;else if(r.allowed_origins instanceof Array)for(var n=0;n<r.allowed_origins.length;n++){var i=(0,Y.D)(r.allowed_origins[n]);if(e.hostname===i.hostname&&e.protocol===i.protocol&&e.port===i.port){t=!0;break}}return t}isDtEnabled(){var e=(0,s.gD)(this.agentIdentifier,"distributed_tracing");return!!e&&!!e.enabled}excludeNewrelicHeader(){var e=(0,s.gD)(this.agentIdentifier,"distributed_tracing");return!!e&&!!e.exclude_newrelic_header}useNewrelicHeaderForCors(){var e=(0,s.gD)(this.agentIdentifier,"distributed_tracing");return!!e&&!1!==e.cors_use_newrelic_header}useTraceContextHeadersForCors(){var e=(0,s.gD)(this.agentIdentifier,"distributed_tracing");return!!e&&!!e.cors_use_tracecontext_headers}}var J=i(9300),Q=i(7295),ee=["load","error","abort","timeout"],te=ee.length,re=s.hR.REQ,ne=s.hR.XHR;class ie extends b{static featureName=J.T;constructor(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,t,J.T,r),this.dt=new X(e),this.handler=(e,t,r,n)=>(0,_.p)(e,t,r,n,this.ee);try{const e={xmlhttprequest:"xhr",fetch:"fetch",beacon:"beacon"};g.gm?.performance?.getEntriesByType("resource").forEach((t=>{if(t.initiatorType in e&&0!==t.responseStatus){const r={status:t.responseStatus},n={rxSize:t.transferSize,duration:Math.floor(t.duration),cbTime:0};oe(r,t.name),this.handler("xhr",[r,n,t.startTime,t.responseEnd,e[t.initiatorType]],void 0,a.K.ajax)}}))}catch(e){}(0,Z.NZ)(this.ee),(0,Z.bX)(this.ee),function(e,t,r,n){function i(e){var t=this;t.totalCbs=0,t.called=0,t.cbTime=0,t.end=w,t.ended=!1,t.xhrGuids={},t.lastSize=null,t.loadCaptureCalled=!1,t.params=this.params||{},t.metrics=this.metrics||{},e.addEventListener("load",(function(r){T(t,e)}),(0,N.jT)(!1)),g.lR||e.addEventListener("progress",(function(e){t.lastSize=e.loaded}),(0,N.jT)(!1))}function o(e){this.params={method:e[0]},oe(this,e[1]),this.metrics={}}function c(t,r){var i=(0,s.oC)(e);i.xpid&&this.sameOrigin&&r.setRequestHeader("X-NewRelic-ID",i.xpid);var o=n.generateTracePayload(this.parsedOrigin);if(o){var a=!1;o.newrelicHeader&&(r.setRequestHeader("newrelic",o.newrelicHeader),a=!0),o.traceContextParentHeader&&(r.setRequestHeader("traceparent",o.traceContextParentHeader),o.traceContextStateHeader&&r.setRequestHeader("tracestate",o.traceContextStateHeader),a=!0),a&&(this.dt=o)}}function d(e,r){var n=this.metrics,i=e[0],o=this;if(n&&i){var a=q(i);a&&(n.txSize=a)}this.startTime=(0,P.t)(),this.body=i,this.listener=function(e){try{"abort"!==e.type||o.loadCaptureCalled||(o.params.aborted=!0),("load"!==e.type||o.called===o.totalCbs&&(o.onloadCalled||"function"!=typeof r.onload)&&"function"==typeof o.end)&&o.end(r)}catch(e){try{t.emit("internal-error",[e])}catch(e){}}};for(var s=0;s<te;s++)r.addEventListener(ee[s],this.listener,(0,N.jT)(!1))}function u(e,t,r){this.cbTime+=e,t?this.onloadCalled=!0:this.called+=1,this.called!==this.totalCbs||!this.onloadCalled&&"function"==typeof r.onload||"function"!=typeof this.end||this.end(r)}function l(e,t){var r=""+W(e)+!!t;this.xhrGuids&&!this.xhrGuids[r]&&(this.xhrGuids[r]=!0,this.totalCbs+=1)}function f(e,t){var r=""+W(e)+!!t;this.xhrGuids&&this.xhrGuids[r]&&(delete this.xhrGuids[r],this.totalCbs-=1)}function h(){this.endTime=(0,P.t)()}function p(e,r){r instanceof ne&&"load"===e[0]&&t.emit("xhr-load-added",[e[1],e[2]],r)}function m(e,r){r instanceof ne&&"load"===e[0]&&t.emit("xhr-load-removed",[e[1],e[2]],r)}function v(e,t,r){t instanceof ne&&("onload"===r&&(this.onload=!0),("load"===(e[0]&&e[0].type)||this.onload)&&(this.xhrCbStart=(0,P.t)()))}function b(e,r){this.xhrCbStart&&t.emit("xhr-cb-time",[(0,P.t)()-this.xhrCbStart,this.onload,r],r)}function y(e){var t,r=e[1]||{};if("string"==typeof e[0]?0===(t=e[0]).length&&g.RI&&(t=""+g.gm.location.href):e[0]&&e[0].url?t=e[0].url:g.gm?.URL&&e[0]&&e[0]instanceof URL?t=e[0].href:"function"==typeof e[0].toString&&(t=e[0].toString()),"string"==typeof t&&0!==t.length){t&&(this.parsedOrigin=(0,Y.D)(t),this.sameOrigin=this.parsedOrigin.sameOrigin);var i=n.generateTracePayload(this.parsedOrigin);if(i&&(i.newrelicHeader||i.traceContextParentHeader))if(e[0]&&e[0].headers)s(e[0].headers,i)&&(this.dt=i);else{var o={};for(var a in r)o[a]=r[a];o.headers=new Headers(r.headers||{}),s(o.headers,i)&&(this.dt=i),e.length>1?e[1]=o:e.push(o)}}function s(e,t){var r=!1;return t.newrelicHeader&&(e.set("newrelic",t.newrelicHeader),r=!0),t.traceContextParentHeader&&(e.set("traceparent",t.traceContextParentHeader),t.traceContextStateHeader&&e.set("tracestate",t.traceContextStateHeader),r=!0),r}}function R(e,t){this.params={},this.metrics={},this.startTime=(0,P.t)(),this.dt=t,e.length>=1&&(this.target=e[0]),e.length>=2&&(this.opts=e[1]);var r,n=this.opts||{},i=this.target;"string"==typeof i?r=i:"object"==typeof i&&i instanceof re?r=i.url:g.gm?.URL&&"object"==typeof i&&i instanceof URL&&(r=i.href),oe(this,r);var o=(""+(i&&i instanceof re&&i.method||n.method||"GET")).toUpperCase();this.params.method=o,this.body=n.body,this.txSize=q(n.body)||0}function x(e,t){if(this.endTime=(0,P.t)(),this.params||(this.params={}),(0,Q.iW)(this.params))return;let n;this.params.status=t?t.status:0,"string"==typeof this.rxSize&&this.rxSize.length>0&&(n=+this.rxSize);const i={txSize:this.txSize,rxSize:n,duration:(0,P.t)()-this.startTime};r("xhr",[this.params,i,this.startTime,this.endTime,"fetch"],this,a.K.ajax)}function w(e){const t=this.params,n=this.metrics;if(!this.ended){this.ended=!0;for(let t=0;t<te;t++)e.removeEventListener(ee[t],this.listener,!1);t.aborted||(0,Q.iW)(t)||(n.duration=(0,P.t)()-this.startTime,this.loadCaptureCalled||4!==e.readyState?null==t.status&&(t.status=0):T(this,e),n.cbTime=this.cbTime,r("xhr",[t,n,this.startTime,this.endTime,"xhr"],this,a.K.ajax))}}function T(e,r){e.params.status=r.status;var n=function(e,t){var r=e.responseType;return"json"===r&&null!==t?t:"arraybuffer"===r||"blob"===r||"json"===r?q(e.response):"text"===r||""===r||void 0===r?q(e.responseText):void 0}(r,e.lastSize);if(n&&(e.metrics.rxSize=n),e.sameOrigin){var i=r.getResponseHeader("X-NewRelic-App-Data");i&&((0,_.p)(C.rs,["Ajax/CrossApplicationTracing/Header/Seen"],void 0,a.K.metrics,t),e.params.cat=i.split(", ").pop())}e.loadCaptureCalled=!0}t.on("new-xhr",i),t.on("open-xhr-start",o),t.on("open-xhr-end",c),t.on("send-xhr-start",d),t.on("xhr-cb-time",u),t.on("xhr-load-added",l),t.on("xhr-load-removed",f),t.on("xhr-resolved",h),t.on("addEventListener-end",p),t.on("removeEventListener-end",m),t.on("fn-end",b),t.on("fetch-before-start",y),t.on("fetch-start",R),t.on("fn-start",v),t.on("fetch-done",x)}(e,this.ee,this.handler,this.dt),this.importAggregator()}}function oe(e,t){var r=(0,Y.D)(t),n=e.params||e;n.hostname=r.hostname,n.port=r.port,n.protocol=r.protocol,n.host=r.hostname+":"+r.port,n.pathname=r.pathname,e.parsedOrigin=r,e.sameOrigin=r.sameOrigin}var ae=i(3738);const{He:se,bD:ce,d3:de,Kp:ue,TZ:le,Lc:fe,uP:he,Rz:ge}=ae;var pe=i(2614);class me extends b{static featureName=t.TZ;#i;constructor(e,r){let n,i=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,r,t.TZ,i),this.replayRunning=!1;try{n=JSON.parse(localStorage.getItem("".concat(pe.H3,"_").concat(pe.uh)))}catch(e){}(0,p.SR)(e)&&this.ee.on(t.G4.RECORD,(()=>this.#o())),this.#a(n)?(this.#i=n?.sessionReplayMode,this.#s()):this.importAggregator(),this.ee.on("err",(e=>{this.replayRunning&&(this.errorNoticed=!0,(0,_.p)(t.G4.ERROR_DURING_REPLAY,[e],void 0,this.featureName,this.ee))})),this.ee.on(t.G4.REPLAY_RUNNING,(e=>{this.replayRunning=e}))}#a(e){return e&&(e.sessionReplayMode===pe.g.FULL||e.sessionReplayMode===pe.g.ERROR)||(0,p.Aw)(this.agentIdentifier)}#c=!1;async#s(e){if(!this.#c){this.#c=!0;try{const{Recorder:t}=await Promise.all([i.e(891),i.e(222)]).then(i.bind(i,2496));this.recorder??=new t({mode:this.#i,agentIdentifier:this.agentIdentifier,trigger:e,ee:this.ee}),this.recorder.startRecording(),this.abortHandler=this.recorder.stopRecording}catch(e){}this.importAggregator({recorder:this.recorder,errorNoticed:this.errorNoticed})}}#o(){this.featAggregate?this.featAggregate.mode!==pe.g.FULL&&this.featAggregate.initializeRecording(pe.g.FULL,!0):(this.#i=pe.g.FULL,this.#s(t.Qb.API),this.recorder&&this.recorder.parent.mode!==pe.g.FULL&&(this.recorder.parent.mode=pe.g.FULL,this.recorder.stopRecording(),this.recorder.startRecording(),this.abortHandler=this.recorder.stopRecording))}}var ve=i(8166);class be extends b{static featureName=ve.T;constructor(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,t,ve.T,r),this.importAggregator()}}var ye=i(993),Re=i(3785);class xe extends b{static featureName=ye.TZ;constructor(e,t){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,t,ye.TZ,r);const n=this.ee;this.ee.on("wrap-logger-end",(function(e){let[t]=e;const{level:r,customAttributes:i}=this;(0,Re.R)(n,t,i,r)})),this.importAggregator()}}new class extends o{constructor(t,r){super(r),g.gm?(this.sharedAggregator=new T({agentIdentifier:this.agentIdentifier}),this.features={},(0,E.bQ)(this.agentIdentifier,this),this.desiredFeatures=new Set(t.features||[]),this.desiredFeatures.add(R),this.runSoftNavOverSpa=[...this.desiredFeatures].some((e=>e.featureName===a.K.softNav)),(0,u.j)(this,t,t.loaderType||"agent"),this.run()):(0,e.R)(21)}get config(){return{info:this.info,init:this.init,loader_config:this.loader_config,runtime:this.runtime}}run(){try{const t=d(this.agentIdentifier),r=[...this.desiredFeatures];r.sort(((e,t)=>a.P[e.featureName]-a.P[t.featureName])),r.forEach((r=>{if(!t[r.featureName]&&r.featureName!==a.K.pageViewEvent)return;if(this.runSoftNavOverSpa&&r.featureName===a.K.spa)return;if(!this.runSoftNavOverSpa&&r.featureName===a.K.softNav)return;(function(e){switch(e){case a.K.ajax:return[a.K.jserrors];case a.K.sessionTrace:return[a.K.ajax,a.K.pageViewEvent];case a.K.sessionReplay:return[a.K.sessionTrace];case a.K.pageViewTiming:return[a.K.pageViewEvent];default:return[]}})(r.featureName).every((e=>e in this.features))||(0,e.R)(36,r.featureName),this.features[r.featureName]=new r(this.agentIdentifier,this.sharedAggregator)}))}catch(t){(0,e.R)(22,t);for(const e in this.features)this.features[e].abortHandler?.();const r=(0,E.Zm)();delete r.initializedAgents[this.agentIdentifier]?.api,delete r.initializedAgents[this.agentIdentifier]?.features,delete this.sharedAggregator;return r.ee.get(this.agentIdentifier).abort(),!1}}}({features:[R,j,class extends b{static featureName=le;constructor(e,t){super(e,t,le,!(arguments.length>2&&void 0!==arguments[2])||arguments[2]);if(!(0,m.V)(this.agentIdentifier))return void(0,l.x3)(this.agentIdentifier,this.featureName);const r=this.ee;let n;(0,Z.vC)(r),this.eventsEE=(0,Z.um)(r),this.eventsEE.on(he,(function(e,t){this.bstStart=(0,P.t)()})),this.eventsEE.on(fe,(function(e,t){(0,_.p)("bst",[e[0],t,this.bstStart,(0,P.t)()],void 0,a.K.sessionTrace,r)})),r.on(ge+de,(function(e){this.time=(0,P.t)(),this.startPath=location.pathname+location.hash})),r.on(ge+ue,(function(e){(0,_.p)("bstHist",[location.pathname+location.hash,this.startPath,this.time],void 0,a.K.sessionTrace,r)}));try{n=new PerformanceObserver((e=>{const t=e.getEntries();(0,_.p)(se,[t],void 0,a.K.sessionTrace,r)})),n.observe({type:ce,buffered:!0})}catch(e){}this.importAggregator({resourceObserver:n})}},me,ie,k,be,B,xe],loaderType:"pro"})})()})();</script>
    <title>タンゴスタ!</title>
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1, minimum-scale=1, maximum-scale=1">
    <link rel="stylesheet" media="all" href="/assets/application-27acae153d372f99594ccf2f7ddb43ce77d2bd3ca9f9e8d2b7664899fae7d0c2.css">
    <meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="7IYoGPjpyiXa6R2r+BgBGAR9cTfCzKGBgfZuJ1jXqmbRVfMJ7l9x8x58iPGNjhEiT1WBYwLDLXxFQrMm5Bfkjg==">
    
    <script type="text/javascript">
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
ga("create","UA-xxxxxx-x","auto");
ga("send","pageview");
</script>

  </head>

  <body id="min_exam" class="min_exam disableselect notranslate">
    <div id="wrapper">
        	    <div id="min_exam_flex_header_wrap">
	    	<div class="min_exam_flex_header">


            <div class="flex_item" data-id="#ja_to_enbox" data-questiontype="1">
	      			<p class="nav_label">B</p>
	      			<p class="nav_ttl">日英四択</p>
	      		</div>


<!-- 今後実装予定
	          <div class="flex_item" data-id="#listeningbox_ja">
 -	      		<p class="nav_label">D</p>
 -	      		<p class="nav_ttl">音声日英四択</p>
 -	      	</div>
-->



				<div class="flex_item" data-id="#sentence_filling_box" data-questiontype="6">
					<p class="nav_label">F</p>
					<p class="nav_ttl">例文四択</p>
				</div>


	      		<div id="exam_timer" class="float_box">
	      			<p class="timer_label">制限時間</p>
	      			<p id="exam_timer_count" class="timer_time">14:57</p>
	      		</div>
	      	</div>

	      	<div id="check_container">
		      	<div id="check_item_wraper" class="check_inner_article clearfix slick-initialized slick-slider">

              
              <div aria-live="polite" class="slick-list draggable"><div class="slick-track" role="listbox" style="opacity: 1; width: 5670px; transform: translate3d(-810px, 0px, 0px);"><div class="check_item slick-slide slick-cloned" data-id="#min_exam41" data-slick-index="-10" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">41</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam42" data-slick-index="-9" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">42</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam43" data-slick-index="-8" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">43</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam44" data-slick-index="-7" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">44</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam45" data-slick-index="-6" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">45</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam46" data-slick-index="-5" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">46</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam47" data-slick-index="-4" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">47</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam48" data-slick-index="-3" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">48</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam49" data-slick-index="-2" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">49</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam50" data-slick-index="-1" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">50</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-current slick-active" data-id="#min_exam01" data-slick-index="0" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide00" style="width: 81px;">
		      			<p class="check_label">01</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam02" data-slick-index="1" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide01" style="width: 81px;">
		      			<p class="check_label">02</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam03" data-slick-index="2" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide02" style="width: 81px;">
		      			<p class="check_label">03</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam04" data-slick-index="3" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide03" style="width: 81px;">
		      			<p class="check_label">04</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam05" data-slick-index="4" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide04" style="width: 81px;">
		      			<p class="check_label">05</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam06" data-slick-index="5" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide05" style="width: 81px;">
		      			<p class="check_label">06</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam07" data-slick-index="6" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide06" style="width: 81px;">
		      			<p class="check_label">07</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam08" data-slick-index="7" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide07" style="width: 81px;">
		      			<p class="check_label">08</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam09" data-slick-index="8" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide08" style="width: 81px;">
		      			<p class="check_label">09</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-active" data-id="#min_exam10" data-slick-index="9" aria-hidden="false" tabindex="-1" role="option" aria-describedby="slick-slide09" style="width: 81px;">
		      			<p class="check_label">10</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam11" data-slick-index="10" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide010" style="width: 81px;">
		      			<p class="check_label">11</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam12" data-slick-index="11" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide011" style="width: 81px;">
		      			<p class="check_label">12</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam13" data-slick-index="12" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide012" style="width: 81px;">
		      			<p class="check_label">13</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam14" data-slick-index="13" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide013" style="width: 81px;">
		      			<p class="check_label">14</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam15" data-slick-index="14" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide014" style="width: 81px;">
		      			<p class="check_label">15</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam16" data-slick-index="15" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide015" style="width: 81px;">
		      			<p class="check_label">16</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam17" data-slick-index="16" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide016" style="width: 81px;">
		      			<p class="check_label">17</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam18" data-slick-index="17" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide017" style="width: 81px;">
		      			<p class="check_label">18</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam19" data-slick-index="18" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide018" style="width: 81px;">
		      			<p class="check_label">19</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam20" data-slick-index="19" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide019" style="width: 81px;">
		      			<p class="check_label">20</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam21" data-slick-index="20" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide020" style="width: 81px;">
		      			<p class="check_label">21</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam22" data-slick-index="21" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide021" style="width: 81px;">
		      			<p class="check_label">22</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam23" data-slick-index="22" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide022" style="width: 81px;">
		      			<p class="check_label">23</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam24" data-slick-index="23" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide023" style="width: 81px;">
		      			<p class="check_label">24</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam25" data-slick-index="24" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide024" style="width: 81px;">
		      			<p class="check_label">25</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam26" data-slick-index="25" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide025" style="width: 81px;">
		      			<p class="check_label">26</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam27" data-slick-index="26" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide026" style="width: 81px;">
		      			<p class="check_label">27</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam28" data-slick-index="27" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide027" style="width: 81px;">
		      			<p class="check_label">28</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam29" data-slick-index="28" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide028" style="width: 81px;">
		      			<p class="check_label">29</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam30" data-slick-index="29" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide029" style="width: 81px;">
		      			<p class="check_label">30</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam31" data-slick-index="30" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide030" style="width: 81px;">
		      			<p class="check_label">31</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam32" data-slick-index="31" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide031" style="width: 81px;">
		      			<p class="check_label">32</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam33" data-slick-index="32" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide032" style="width: 81px;">
		      			<p class="check_label">33</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam34" data-slick-index="33" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide033" style="width: 81px;">
		      			<p class="check_label">34</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam35" data-slick-index="34" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide034" style="width: 81px;">
		      			<p class="check_label">35</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam36" data-slick-index="35" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide035" style="width: 81px;">
		      			<p class="check_label">36</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam37" data-slick-index="36" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide036" style="width: 81px;">
		      			<p class="check_label">37</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam38" data-slick-index="37" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide037" style="width: 81px;">
		      			<p class="check_label">38</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam39" data-slick-index="38" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide038" style="width: 81px;">
		      			<p class="check_label">39</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam40" data-slick-index="39" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide039" style="width: 81px;">
		      			<p class="check_label">40</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam41" data-slick-index="40" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide040" style="width: 81px;">
		      			<p class="check_label">41</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam42" data-slick-index="41" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide041" style="width: 81px;">
		      			<p class="check_label">42</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam43" data-slick-index="42" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide042" style="width: 81px;">
		      			<p class="check_label">43</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam44" data-slick-index="43" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide043" style="width: 81px;">
		      			<p class="check_label">44</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam45" data-slick-index="44" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide044" style="width: 81px;">
		      			<p class="check_label">45</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam46" data-slick-index="45" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide045" style="width: 81px;">
		      			<p class="check_label">46</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam47" data-slick-index="46" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide046" style="width: 81px;">
		      			<p class="check_label">47</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam48" data-slick-index="47" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide047" style="width: 81px;">
		      			<p class="check_label">48</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam49" data-slick-index="48" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide048" style="width: 81px;">
		      			<p class="check_label">49</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide" data-id="#min_exam50" data-slick-index="49" aria-hidden="true" tabindex="-1" role="option" aria-describedby="slick-slide049" style="width: 81px;">
		      			<p class="check_label">50</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam01" data-slick-index="50" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">01</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam02" data-slick-index="51" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">02</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam03" data-slick-index="52" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">03</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam04" data-slick-index="53" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">04</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam05" data-slick-index="54" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">05</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam06" data-slick-index="55" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">06</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam07" data-slick-index="56" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">07</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam08" data-slick-index="57" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">08</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam09" data-slick-index="58" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">09</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div><div class="check_item slick-slide slick-cloned" data-id="#min_exam10" data-slick-index="59" aria-hidden="true" tabindex="-1" style="width: 81px;">
		      			<p class="check_label">10</p>
		      			<p class="check_icon"><i class="fa fa-check" aria-hidden="true"></i></p>
		      		</div></div></div>

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

              
              

		      		
		      	
	      	</div>
	      	</div>

	      </div><!-- min_exam_header_wrap -->

        <div class="min_exam_container" style="margin-top: 90px;">
          
          <div id="contents" class="">
            <div id="exam_questions_wrapper" data-exam-id="747150" data-additional-exam-id="2288726">
  <div id="exam_kyebord" class="ui-keyboard-input ui-widget-content ui-corner-all" aria-haspopup="true" role="textbox"></div>


    <div id="ja_to_enbox" class="gray-container sec">
      <div class="tablet_inner_article">
        <div class="middle_article">
          <div class="exam_label"><p>B</p></div>
          <p class="exam_heading">日本語に合う適切な英語を一つ選びなさい。</p>
          <p class="exam_points">各1点</p>
        </div>
      </div>
    </div>

      <div id="min_exam01" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>01</p></div>
            <p class="exam_word">しばらくの間</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="0" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795761" data-minexam-id="01">
              <a href="#" class="exam_btn default">for a while</a>
              <a href="#" class="exam_btn default">at once</a>
              <a href="#" class="exam_btn default">at last</a>
              <a href="#" class="exam_btn default">all day long</a>
          </div>
        </div>
      </div>
      <div id="min_exam02" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>02</p></div>
            <p class="exam_word">～のために</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="1" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795762" data-minexam-id="02">
              <a href="#" class="exam_btn default">take the place of ～</a>
              <a href="#" class="exam_btn default">in danger of ～</a>
              <a href="#" class="exam_btn default">for the sake of ～</a>
              <a href="#" class="exam_btn default">in search of ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam03" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>03</p></div>
            <p class="exam_word">～であることがわかる</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="2" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795763" data-minexam-id="03">
              <a href="#" class="exam_btn default">show up ～</a>
              <a href="#" class="exam_btn default">turn out to be ～</a>
              <a href="#" class="exam_btn default">reflect on [upon] ～</a>
              <a href="#" class="exam_btn default">turn over ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam04" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>04</p></div>
            <p class="exam_word">…することができない</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="3" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795764" data-minexam-id="04">
              <a href="#" class="exam_btn default">come to do</a>
              <a href="#" class="exam_btn default">be unable to do</a>
              <a href="#" class="exam_btn default">take time to do</a>
              <a href="#" class="exam_btn default">feel free to do</a>
          </div>
        </div>
      </div>
      <div id="min_exam05" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>05</p></div>
            <p class="exam_word">自分の意志が通じる</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="4" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795765" data-minexam-id="05">
              <a href="#" class="exam_btn default">make oneself understood</a>
              <a href="#" class="exam_btn default">take a walk</a>
              <a href="#" class="exam_btn default">make it</a>
              <a href="#" class="exam_btn default">show up</a>
          </div>
        </div>
      </div>
      <div id="min_exam06" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>06</p></div>
            <p class="exam_word">順番に</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="5" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795766" data-minexam-id="06">
              <a href="#" class="exam_btn default">in turn</a>
              <a href="#" class="exam_btn default">little by little</a>
              <a href="#" class="exam_btn default">later on</a>
              <a href="#" class="exam_btn default">for sure [certain]</a>
          </div>
        </div>
      </div>
      <div id="min_exam07" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>07</p></div>
            <p class="exam_word">AかBのどちらか</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="6" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795767" data-minexam-id="07">
              <a href="#" class="exam_btn default">either A or B</a>
              <a href="#" class="exam_btn default">such A as B</a>
              <a href="#" class="exam_btn default">not only A but B</a>
              <a href="#" class="exam_btn default">both A and B</a>
          </div>
        </div>
      </div>
      <div id="min_exam08" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>08</p></div>
            <p class="exam_word">～を必要とする</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="7" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795768" data-minexam-id="08">
              <a href="#" class="exam_btn default">call for ～</a>
              <a href="#" class="exam_btn default">reflect on ～</a>
              <a href="#" class="exam_btn default">call off ～</a>
              <a href="#" class="exam_btn default">bring up ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam09" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>09</p></div>
            <p class="exam_word">～のことで有名だ</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="8" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795769" data-minexam-id="09">
              <a href="#" class="exam_btn default">used to be ～</a>
              <a href="#" class="exam_btn default">be known for ～</a>
              <a href="#" class="exam_btn default">turn out to be ～</a>
              <a href="#" class="exam_btn default">lie in ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam10" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>10</p></div>
            <p class="exam_word">～を身につける</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="9" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795770" data-minexam-id="10">
              <a href="#" class="exam_btn default">put on ～</a>
              <a href="#" class="exam_btn default">put away ～</a>
              <a href="#" class="exam_btn default">run after ～</a>
              <a href="#" class="exam_btn default">take off ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam11" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>11</p></div>
            <p class="exam_word">…することをやめる</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="10" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795771" data-minexam-id="11">
              <a href="#" class="exam_btn default">go on doing</a>
              <a href="#" class="exam_btn default">be used to doing</a>
              <a href="#" class="exam_btn default">give up doing</a>
              <a href="#" class="exam_btn default">feel like doing</a>
          </div>
        </div>
      </div>
      <div id="min_exam12" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>12</p></div>
            <p class="exam_word">AもBも（両方とも）</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="11" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795772" data-minexam-id="12">
              <a href="#" class="exam_btn default">both A and B</a>
              <a href="#" class="exam_btn default">not A but B</a>
              <a href="#" class="exam_btn default">such A as B</a>
              <a href="#" class="exam_btn default">either A or B</a>
          </div>
        </div>
      </div>
      <div id="min_exam13" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>13</p></div>
            <p class="exam_word">直ちに</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="12" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795773" data-minexam-id="13">
              <a href="#" class="exam_btn default">in turn</a>
              <a href="#" class="exam_btn default">right away [off]</a>
              <a href="#" class="exam_btn default">the other day</a>
              <a href="#" class="exam_btn default">for a while</a>
          </div>
        </div>
      </div>
      <div id="min_exam14" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>14</p></div>
            <p class="exam_word">少しずつ</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="13" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795774" data-minexam-id="14">
              <a href="#" class="exam_btn default">in turn</a>
              <a href="#" class="exam_btn default">later on</a>
              <a href="#" class="exam_btn default">little by little</a>
              <a href="#" class="exam_btn default">in advance</a>
          </div>
        </div>
      </div>
      <div id="min_exam15" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>15</p></div>
            <p class="exam_word">間もなく</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="14" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795775" data-minexam-id="15">
              <a href="#" class="exam_btn default">at first</a>
              <a href="#" class="exam_btn default">before long</a>
              <a href="#" class="exam_btn default">for a long time</a>
              <a href="#" class="exam_btn default">at last</a>
          </div>
        </div>
      </div>
      <div id="min_exam16" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>16</p></div>
            <p class="exam_word">…し続ける</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="15" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795776" data-minexam-id="16">
              <a href="#" class="exam_btn default">give up doing</a>
              <a href="#" class="exam_btn default">be used to doing</a>
              <a href="#" class="exam_btn default">go on doing</a>
              <a href="#" class="exam_btn default">feel like doing</a>
          </div>
        </div>
      </div>
      <div id="min_exam17" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>17</p></div>
            <p class="exam_word">～を試着する</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="16" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795777" data-minexam-id="17">
              <a href="#" class="exam_btn default">try on ～</a>
              <a href="#" class="exam_btn default">turn on ～</a>
              <a href="#" class="exam_btn default">call on ～</a>
              <a href="#" class="exam_btn default">turn off ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam18" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>18</p></div>
            <p class="exam_word">きっと</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="17" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795778" data-minexam-id="18">
              <a href="#" class="exam_btn default">no doubt</a>
              <a href="#" class="exam_btn default">in the first place</a>
              <a href="#" class="exam_btn default">in fact</a>
              <a href="#" class="exam_btn default">in other words</a>
          </div>
        </div>
      </div>
      <div id="min_exam19" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>19</p></div>
            <p class="exam_word">Aを（Bに）伝える</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="18" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795779" data-minexam-id="19">
              <a href="#" class="exam_btn default">get together with A (for B)</a>
              <a href="#" class="exam_btn default">pass A on (to B)</a>
              <a href="#" class="exam_btn default">have A in common (with B) </a>
              <a href="#" class="exam_btn default">look to A (for B)</a>
          </div>
        </div>
      </div>
      <div id="min_exam20" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>20</p></div>
            <p class="exam_word">～を点ける</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="19" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795780" data-minexam-id="20">
              <a href="#" class="exam_btn default">call on ～</a>
              <a href="#" class="exam_btn default">turn on ～</a>
              <a href="#" class="exam_btn default">turn over ～</a>
              <a href="#" class="exam_btn default">bring up ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam21" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>21</p></div>
            <p class="exam_word">～ごとに</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="20" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795781" data-minexam-id="21">
              <a href="#" class="exam_btn default">a series of ～</a>
              <a href="#" class="exam_btn default">each other ～</a>
              <a href="#" class="exam_btn default">one after another ～</a>
              <a href="#" class="exam_btn default">every other ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam22" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>22</p></div>
            <p class="exam_word">～ほども多く（の）</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="21" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795782" data-minexam-id="22">
              <a href="#" class="exam_btn default">as many [much] as ～</a>
              <a href="#" class="exam_btn default">at the age of ～</a>
              <a href="#" class="exam_btn default">in danger of ～</a>
              <a href="#" class="exam_btn default">every other ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam23" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>23</p></div>
            <p class="exam_word">～もまた</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="22" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795783" data-minexam-id="23">
              <a href="#" class="exam_btn default">as well</a>
              <a href="#" class="exam_btn default">at once</a>
              <a href="#" class="exam_btn default">at present</a>
              <a href="#" class="exam_btn default">for a while</a>
          </div>
        </div>
      </div>
      <div id="min_exam24" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>24</p></div>
            <p class="exam_word">お互い</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="23" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795784" data-minexam-id="24">
              <a href="#" class="exam_btn default">each other</a>
              <a href="#" class="exam_btn default">by nature</a>
              <a href="#" class="exam_btn default">so far</a>
              <a href="#" class="exam_btn default">in turn</a>
          </div>
        </div>
      </div>
      <div id="min_exam25" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>25</p></div>
            <p class="exam_word">現在（は）</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="24" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795785" data-minexam-id="25">
              <a href="#" class="exam_btn default">by nature</a>
              <a href="#" class="exam_btn default">at present</a>
              <a href="#" class="exam_btn default">at once</a>
              <a href="#" class="exam_btn default">on time</a>
          </div>
        </div>
      </div>
      <div id="min_exam26" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>26</p></div>
            <p class="exam_word">～を消す</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="25" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795786" data-minexam-id="26">
              <a href="#" class="exam_btn default">show up ～</a>
              <a href="#" class="exam_btn default">turn off ～</a>
              <a href="#" class="exam_btn default">call off ～</a>
              <a href="#" class="exam_btn default">try on ～</a>
          </div>
        </div>
      </div>
      <div id="min_exam27" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>27</p></div>
            <p class="exam_word">確かに</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="26" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795787" data-minexam-id="27">
              <a href="#" class="exam_btn default">at present</a>
              <a href="#" class="exam_btn default">by nature</a>
              <a href="#" class="exam_btn default">for sure [certain]</a>
              <a href="#" class="exam_btn default">for nothing</a>
          </div>
        </div>
      </div>
      <div id="min_exam28" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>28</p></div>
            <p class="exam_word">うまくいく</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="27" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795788" data-minexam-id="28">
              <a href="#" class="exam_btn default">make it</a>
              <a href="#" class="exam_btn default">give up</a>
              <a href="#" class="exam_btn default">hear of</a>
              <a href="#" class="exam_btn default">carry out</a>
          </div>
        </div>
      </div>
      <div id="min_exam29" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>29</p></div>
            <p class="exam_word">AをBと区別する</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="28" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795789" data-minexam-id="29">
              <a href="#" class="exam_btn default">hand down A to B</a>
              <a href="#" class="exam_btn default">give A to B</a>
              <a href="#" class="exam_btn default">take A for B</a>
              <a href="#" class="exam_btn default">tell A from B</a>
          </div>
        </div>
      </div>
      <div id="min_exam30" class="white-container mt5">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>30</p></div>
            <p class="exam_word">～をひっくり返す</p>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="29" data-question-type="1" data-name="ja_to_enbox" data-question-id="60795790" data-minexam-id="30">
              <a href="#" class="exam_btn default">try on ～</a>
              <a href="#" class="exam_btn default">call on ～</a>
              <a href="#" class="exam_btn default">turn off ～</a>
              <a href="#" class="exam_btn default">turn over ～</a>
          </div>
        </div>
      </div>





    <div id="sentence_filling_box" class="gray-container sec">
      <div class="tablet_inner_article">
        <div class="middle_article">
          <div class="exam_label"><p>F</p></div>
          <p class="exam_heading">空所に入る適当な語（句）を１つ選びなさい。</p>
          <p class="exam_points">各1点</p>
        </div>
      </div>
    </div>

      <div id="min_exam31" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>31</p></div>
              <div class="exam_sentence_filling_question">
                She was sitting by the window (　　).
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼女はいつものように窓際に座っていた。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="0" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795791" data-minexam-id="31">
              <a href="#" class="exam_btn default">at least</a>
              <a href="#" class="exam_btn default">as usual</a>
              <a href="#" class="exam_btn default">by mistake</a>
              <a href="#" class="exam_btn default">at last</a>
          </div>
        </div>
      </div>
      <div id="min_exam32" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>32</p></div>
              <div class="exam_sentence_filling_question">
                His family were (　　) friendly (　　).
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼の家族は相変わらず気さくだった。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="1" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795792" data-minexam-id="32">
              <a href="#" class="exam_btn default">as, as ever</a>
              <a href="#" class="exam_btn default">as, as possible</a>
              <a href="#" class="exam_btn default">from, on</a>
              <a href="#" class="exam_btn default">not, at all</a>
          </div>
        </div>
      </div>
      <div id="min_exam33" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>33</p></div>
              <div class="exam_sentence_filling_question">
                The empty house is (　　) falling down.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                その空き家は倒壊の恐れがある。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="2" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795793" data-minexam-id="33">
              <a href="#" class="exam_btn default">in search of</a>
              <a href="#" class="exam_btn default">by way of</a>
              <a href="#" class="exam_btn default">in danger of</a>
              <a href="#" class="exam_btn default">for the sake of</a>
          </div>
        </div>
      </div>
      <div id="min_exam34" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>34</p></div>
              <div class="exam_sentence_filling_question">
                She’s (　　) getting up early.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼女は早起きに慣れている。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="3" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795794" data-minexam-id="34">
              <a href="#" class="exam_btn default">about to</a>
              <a href="#" class="exam_btn default">good at</a>
              <a href="#" class="exam_btn default">willing to</a>
              <a href="#" class="exam_btn default">used to</a>
          </div>
        </div>
      </div>
      <div id="min_exam35" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>35</p></div>
              <div class="exam_sentence_filling_question">
                A little salt (　　) the flavor of the meat.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                少量の塩で肉の旨味を引き出せる。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="4" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795795" data-minexam-id="35">
              <a href="#" class="exam_btn default">puts away</a>
              <a href="#" class="exam_btn default">brings out</a>
              <a href="#" class="exam_btn default">calls off</a>
              <a href="#" class="exam_btn default">turns on</a>
          </div>
        </div>
      </div>
      <div id="min_exam36" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>36</p></div>
              <div class="exam_sentence_filling_question">
                She loves cooking. (　　), she posts many original menus.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼女は料理が大好きだ。実際，オリジナルメニューをたくさん投稿している。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="5" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795796" data-minexam-id="36">
              <a href="#" class="exam_btn default">In advance</a>
              <a href="#" class="exam_btn default">By nature</a>
              <a href="#" class="exam_btn default">In fact</a>
              <a href="#" class="exam_btn default">At a loss</a>
          </div>
        </div>
      </div>
      <div id="min_exam37" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>37</p></div>
              <div class="exam_sentence_filling_question">
                We haven’t noticed anything wrong (　　).
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                私たちはこれまでのところ異常な点には何も気づいていない。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="6" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795797" data-minexam-id="37">
              <a href="#" class="exam_btn default">in fact</a>
              <a href="#" class="exam_btn default">no doubt</a>
              <a href="#" class="exam_btn default">so far</a>
              <a href="#" class="exam_btn default">in the first place</a>
          </div>
        </div>
      </div>
      <div id="min_exam38" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>38</p></div>
              <div class="exam_sentence_filling_question">
                (　　), I got a perfect score in math.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                みんなが驚いたことに，私は数学で満点を取った。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="7" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795798" data-minexam-id="38">
              <a href="#" class="exam_btn default">Make everyone’s way</a>
              <a href="#" class="exam_btn default">To everyone’s surprise</a>
              <a href="#" class="exam_btn default">For the sake everyone</a>
              <a href="#" class="exam_btn default">In place of everyone</a>
          </div>
        </div>
      </div>
      <div id="min_exam39" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>39</p></div>
              <div class="exam_sentence_filling_question">
                She started acting (　　) nine.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼女は9歳のときに演劇活動を始めた。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="8" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795799" data-minexam-id="39">
              <a href="#" class="exam_btn default">face to face with</a>
              <a href="#" class="exam_btn default">for the time of</a>
              <a href="#" class="exam_btn default">at the age of</a>
              <a href="#" class="exam_btn default">at the same time as</a>
          </div>
        </div>
      </div>
      <div id="min_exam40" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>40</p></div>
              <div class="exam_sentence_filling_question">
                Leadership (　　) age.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                リーダーシップは年齢と無関係だ。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="9" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795800" data-minexam-id="40">
              <a href="#" class="exam_btn default">has nothing to do with</a>
              <a href="#" class="exam_btn default">does away with</a>
              <a href="#" class="exam_btn default">catches up to</a>
              <a href="#" class="exam_btn default">keeps up with</a>
          </div>
        </div>
      </div>
      <div id="min_exam41" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>41</p></div>
              <div class="exam_sentence_filling_question">
                I was shocked and (　　) for words.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                私はショックを受けて，何と言ってよいのか困った。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="10" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795801" data-minexam-id="41">
              <a href="#" class="exam_btn default">for a while</a>
              <a href="#" class="exam_btn default">at the most</a>
              <a href="#" class="exam_btn default">in a hurry</a>
              <a href="#" class="exam_btn default">at a loss</a>
          </div>
        </div>
      </div>
      <div id="min_exam42" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>42</p></div>
              <div class="exam_sentence_filling_question">
                We (　　) the route.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                私たちはそのルートに決めた。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="11" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795802" data-minexam-id="42">
              <a href="#" class="exam_btn default">called for</a>
              <a href="#" class="exam_btn default">tried on</a>
              <a href="#" class="exam_btn default">decided on</a>
              <a href="#" class="exam_btn default">believed in</a>
          </div>
        </div>
      </div>
      <div id="min_exam43" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>43</p></div>
              <div class="exam_sentence_filling_question">
                I happened to see your sister (　　).
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                先日たまたまあなたのお姉さんに会いました。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="12" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795803" data-minexam-id="43">
              <a href="#" class="exam_btn default">the other day</a>
              <a href="#" class="exam_btn default">so far</a>
              <a href="#" class="exam_btn default">in turn</a>
              <a href="#" class="exam_btn default">for a while</a>
          </div>
        </div>
      </div>
      <div id="min_exam44" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>44</p></div>
              <div class="exam_sentence_filling_question">
                (　　) this printer.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                このプリンターはどこか調子が悪い。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="13" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795804" data-minexam-id="44">
              <a href="#" class="exam_btn default">Have nothing to do with</a>
              <a href="#" class="exam_btn default">For the sake of</a>
              <a href="#" class="exam_btn default">Something is wrong with</a>
              <a href="#" class="exam_btn default">Turn out to be</a>
          </div>
        </div>
      </div>
      <div id="min_exam45" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>45</p></div>
              <div class="exam_sentence_filling_question">
                It’s a perfect day for (　　).
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                散歩するには絶好の日和だ。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="14" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795805" data-minexam-id="45">
              <a href="#" class="exam_btn default">taking a walk</a>
              <a href="#" class="exam_btn default">making it</a>
              <a href="#" class="exam_btn default">taking time</a>
              <a href="#" class="exam_btn default">showing up</a>
          </div>
        </div>
      </div>
      <div id="min_exam46" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>46</p></div>
              <div class="exam_sentence_filling_question">
                He was born and (　　) in Boston.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼はボストンで生まれ育った。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="15" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795806" data-minexam-id="46">
              <a href="#" class="exam_btn default">brought up</a>
              <a href="#" class="exam_btn default">called off</a>
              <a href="#" class="exam_btn default">called for</a>
              <a href="#" class="exam_btn default">called on</a>
          </div>
        </div>
      </div>
      <div id="min_exam47" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>47</p></div>
              <div class="exam_sentence_filling_question">
                Our order (　　) arrive.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                私たちの注文は来るのに時間がかかった。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="16" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795807" data-minexam-id="47">
              <a href="#" class="exam_btn default">took off to</a>
              <a href="#" class="exam_btn default">made it to</a>
              <a href="#" class="exam_btn default">took part in to</a>
              <a href="#" class="exam_btn default">took time to</a>
          </div>
        </div>
      </div>
      <div id="min_exam48" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>48</p></div>
              <div class="exam_sentence_filling_question">
                They (　　) late for the party.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                彼らはパーティーに遅れて現れた。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="17" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795808" data-minexam-id="48">
              <a href="#" class="exam_btn default">called off</a>
              <a href="#" class="exam_btn default">brought up</a>
              <a href="#" class="exam_btn default">showed up</a>
              <a href="#" class="exam_btn default">went wrong</a>
          </div>
        </div>
      </div>
      <div id="min_exam49" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>49</p></div>
              <div class="exam_sentence_filling_question">
                (　　) I know, it’s the best method.
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                私が知る限りでは，それが最善策だ。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="18" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795809" data-minexam-id="49">
              <a href="#" class="exam_btn default">Far from</a>
              <a href="#" class="exam_btn default">No longer</a>
              <a href="#" class="exam_btn default">Even if</a>
              <a href="#" class="exam_btn default">As far as</a>
          </div>
        </div>
      </div>
      <div id="min_exam50" class="white-container">
        <div class="tablet_inner_article">
          <div class="exam_inner_area">
            <div class="exam_inner_label"><p>50</p></div>
              <div class="exam_sentence_filling_question">
                The reporters asked questions (　　).
              </div>
          </div>
          <div class="exam_inner_area">
              <div class="exam_sentence_filling_question">
                記者たちは次々と質問をした。
              </div>
          </div>
          <div class="exam_inner_area exam_choice_area" data-index="19" data-question-type="6" data-name="sentence_filling_box" data-question-id="60795810" data-minexam-id="50">
              <a href="#" class="exam_btn default">on the other hand</a>
              <a href="#" class="exam_btn default">one after another</a>
              <a href="#" class="exam_btn default">for sure</a>
              <a href="#" class="exam_btn default">in the first place</a>
          </div>
        </div>
      </div>


  <a href="#back-modal" class="back-modal" style="display:none;" data-modaal-scope="modaal_1723051562523fecaa8f0eeb48">Show</a>
  <div id="back-modal" style="display:none;">
    <p class="flex_article">テストの途中では戻れません。</p>
    <div class="modaal-confirm-wrap">
      <button type="button" class="modaal-confirm-btn modaal-ok" aria-label="Confirm">OK</button>
    </div>
  </div>

  <a href="#expired-modal" class="expired-modal" style="display:none;" data-modaal-scope="modaal_17230515625237e9d1ca1043b1">Show</a>
  <div id="expired-modal" style="display:none;">
    <p class="flex_article">解答時間が過ぎました。<br>答案を提出します。</p>
    <div class="modaal-confirm-wrap">
      <button type="button" class="modaal-confirm-btn modaal-ok" aria-label="Confirm">OK</button>
    </div>
  </div>

  <form format="json" id="min_exam_post" action="/students/exam/create_result" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="7IYoGPjpyiXa6R2r+BgBGAR9cTfCzKGBgfZuJ1jXqmbRVfMJ7l9x8x58iPGNjhEiT1WBYwLDLXxFQrMm5Bfkjg==">
    <input type="hidden" name="exam_data" id="exam_data" value="">
    <input type="hidden" name="answer_data" id="answer_data" value="">
</form>
  <script>
//<![CDATA[

      window.exam_id = 2288726;
    window.student_id = 184117;
    window.school_class_id = 10839;
    window.unanswered = [60795761, 60795762, 60795763, 60795764, 60795765, 60795766, 60795767, 60795768, 60795769, 60795770, 60795771, 60795772, 60795773, 60795774, 60795775, 60795776, 60795777, 60795778, 60795779, 60795780, 60795781, 60795782, 60795783, 60795784, 60795785, 60795786, 60795787, 60795788, 60795789, 60795790, 60795791, 60795792, 60795793, 60795794, 60795795, 60795796, 60795797, 60795798, 60795799, 60795800, 60795801, 60795802, 60795803, 60795804, 60795805, 60795806, 60795807, 60795808, 60795809, 60795810];
    window.deadline = 15;

//]]>
</script></div>

<div id="min_exam_footer">
  <div id="js-exam_confirm">
    <p>未解答問題が<span id="js-unanswered_count">50</span>問あります</p>
    <button name="button" type="submit" class="submit blue" data-disable-with="答案を提出する" data-modaal-scope="modaal_1723051562606cd30653281a5f">答案を提出する</button>
  </div>
</div>

<div id="confirm-modal" style="display:none;">
  <p class="flex_article">「OK」を押すと解答内容を修正できなくなります。<br>答案を提出してよろしいですか？</p>
  <div class="modaal-confirm-wrap">
    <button type="button" class="modaal-confirm-btn modaal-cancel" aria-label="Confirm">キャンセル</button>
    <button id="js-exam_submit" type="button" class="modaal-confirm-btn modaal-ok" aria-label="Confirm">OK</button>
  </div>
</div>

          </div>
        </div><!-- min_exam_container -->
    </div>
    <script src="/assets/application-dbb22645c07e6e01a431573bc0df811961794f998154e49f58c2079fe23deb81.js"></script>
  

</body></html>
