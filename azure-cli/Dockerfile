FROM azure-cli

RUN pip install --upgrade \
	--pre azure-cli \
	--extra-index-url https://azurecliprod.blob.core.windows.net/edge \
    --no-cache-dir

ENTRYPOINT [ "az"  ]
