# NextJS ONNX Runtime Web Template

This is a NextJS template that is meant to be used to give you a starting point to doing inferencing on the client with PyTorch using ONNX Runtime web. This react template has all the helper functions and logic needed to process images and run inference in the browser for imagenet models like squeezenet, resnet and mobilenet.

This template is configured with webpack, onnxruntime-web, react, typescript and dev environments for testing.

## Run the development server:

First, run the development server:

```bash
npm run start
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Deploy on Azure with Static Web Apps

Deploy your site with Azure. Checkout the docs for deploying to a Static Web Apps resource.

- [Deploy with Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/)


## Credits/Resources

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### ONNX Runtime Web Demo

ONNX Runtime Web demo is an interactive demo portal showing real use cases running ONNX Runtime Web in VueJS. It currently supports four examples for you to quickly experience the power of ONNX Runtime Web.

- [ONNX Runtime Web Demo for more models](https://github.com/microsoft/onnxruntime-web-demo)

### How to Run Machine-Learning Models in the Browser using ONNX

In this tutorial we will dive into onnxruntime-web by deploying a pre-trained PyTorch model to the browser. 

- [How to Run Machine-Learning Models in the Browser using ONNX](https://hackernoon.com/how-to-run-machine-learning-models-in-the-browser-using-onnx)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
