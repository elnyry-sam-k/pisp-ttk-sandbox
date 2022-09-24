# Running PISP TTK Sandbox

1. Clone the repository
```
git clone https://github.com/vijayg10/pisp-ttk-sandbox.git
cd pisp-ttk-sandbox
```
2. Run simulators
```
docker-compose up
```
3. Open TTK UI on http://localhost:6060
4. Goto `Test Runner` and open `Collection Managaer`
5. Click on `Import File` and load the TTK test case `thirdparty.json` from the folder `test-cases`
6. Select the imported file in the collection manager
7. Click on the button `Run`
8. Observe the requests and responses in each test case
9. Open monitoring page in a separate tab or window (http://localhost:6060/admin/monitoring or use the option on the left pane) and "run" the file (test cases) again to view the requests and responses (expand on each to see the messages and synchronous responses)
10. For customizing and tweaking data or further exploration, use the "edit" option (on the right side) of each test case to view the various options in the requests (For further documentation on usage, refer to TTK docs: https://github.com/mojaloop/ml-testing-toolkit/blob/master/documents/User-Guide.md)
