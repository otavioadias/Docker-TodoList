FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todotests
ADD node_modules.tar.gz .
COPY ./ .
ENTRYPOINT ["npm"]
CMD ["test"]
