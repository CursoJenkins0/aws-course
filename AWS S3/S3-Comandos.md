# Crear un Bucket S3 de Amazon
aws s3 mb s3://minewbucketdejulian

# Listar los Buckets S3
aws s3 ls

# Cargar un archivo al Bucket S3
aws s3 cp miarchivodeprueba s3://minewbucketdejulian

# Listar los contenidos del Bucket S3
aws s3 ls s3://minewbucketdejulian

# Eliminar el Bucket S3
aws s3 rb --force s3://minewbucketdejulian

