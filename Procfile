css: npx esbuild --bundle sb/main.css --outfile=public/css/main.css --watch
java_server: npx shadow-cljs server
# storybook_js: cd sb && npm run storybook
storybook_cljs: sleep 10 && npx shadow-cljs watch storybook
cljs_ui: sleep 10 && npx shadow-cljs watch ui
browser_tests: sleep 10 && npx shadow-cljs watch browser-tests # To run: open http://localhost:8000
unit_tests: sleep 10 && npx shadow-cljs watch unit-tests # To run: node out/unit_tests.js
