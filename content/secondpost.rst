second_post
###########

:date: 2014-12-13 18:32
:category: Test
 

.. code:: bash

    import sh, cryptography


.. code:: bash 

    from cryptography.hazmat.backends import default_backend
    from cryptography.hazmat.primitives.asymmetric import rsa

.. code:: bash 

    """
    source:
    
    https://cryptography.io/en/latest/hazmat/primitives/asymmetric/rsa/
    """
    
    private_key = rsa.generate_private_key(
         public_exponent=65537,
         key_size=2048,
         backend=default_backend()
    )

