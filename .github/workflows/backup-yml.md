# name: Deploy to GitHub Pages
# on:
#   push:
#     branches:
#       - main
# permissions:
#   contents: write

# jobs:
#   build-and-deploy:
#     runs-on: ubuntu-latest
#     steps:
#       - name: Checkout 🛎️
#         uses: actions/checkout@v3
#         with:
#           lfs: true

#       - name: Deploy 🚀
#         uses: JamesIves/github-pages-deploy-action@v4
#         with:
#           # deploy_key: ${{ secrets.PORTFOLIO_ACTIONS }}
#           folder: ./
