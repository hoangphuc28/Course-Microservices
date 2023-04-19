mkdir config internal pb pkg
cd internal mkdir delivery model repo usecase
Library:
go get google.golang.org/grpc
go get github.com/spf13/viper
go get  gorm.io/gorm
go get gorm.io/driver/mysql
go get github.com/speps/go-hashids/v2
go get golang.org/x/crypto/bcrypt
go get github.com/gin-gonic/gin
go get github.com/golang-jwt/jwt/v4
go get gopkg.in/gomail.v2
go get github.com/k3a/html2text
go get github.com/aws/aws-sdk-go/aws