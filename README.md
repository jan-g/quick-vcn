# Set up an OCI VCN and components quickly

## To install:

    pip install -e .

## To use:

    quick-vcn --profile YOUR-PROFILE \
        --compartment YOUR-COMPARTMENT-NAME \
        --region uk-london-1 \
        [ --vcn-name "net" ] \
        [ --vcn-cidr 10.0.0.0/16 ] \
        [ --subnet-name "sub" ] \
        [ --subnet-cidr 10.0.0.0/24 ]
